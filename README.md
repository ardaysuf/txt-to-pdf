import  com.aspose.cells.Workbook;      
public class AsposeCells {
    public static void main(String[] args) {
        try {
            Workbook workbook = new Workbook("input.txt");
            workbook.save("Output.pdf");
        } catch (Exception e) {
        }
    }
}
