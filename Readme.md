# Calculator

by Saharat Bonnao,
673450201-5,
Computer and Infomation Science, KKU

# การรับและการแสดงผลข้อมูล

รับข้อมูลจากผู้ใช้งาน และทำงานผ่านการกดปุ่มเพื่อคำนวนตัวเลข

## ปุ่มบวก
int iResult = iNum1 + iNum2;
```
private void button1_Click(object sender, EventArgs e)
{
    // ข้อความตัวอักษร
    string inputNum1 = num1.Text;
    string inputNum2 = num2.Text;
    // convert string to number (integer)
    int iNum1 = Int32.Parse(inputNum1);
    int iNum2 = Int32.Parse(inputNum2);
    // int ทำให้เราสามารถทำการ + - * / ได้
    int iResult = iNum1 + iNum2;
    // ที่ตัวแปรชื่อ result
    // มีคุณสมบัติชื่อ Text
    result.Text = iResult.ToString();
}
```

### รับข้อมูล
string inputNum1 =num3.Text;
string inputNum2 = num2.Text;

### แปลงชนิดของข้อมูล
 int iNum1 = Int32.Parse(inputNum1);
 int iNum2 = Int32.Parse(inputNum2);

### คำนวนผลลัพท์
 int iResult = iNum1 + iNum2;
### แสดงผล
result.Text = iResult.ToString();
## ปุ่มลบ
int iResult = iNum1 - iNum2;
## ปุ่มคูณ
int iResult = iNum1 * iNum2;
## ปุ่มหาร
int iResult = iNum1 / iNum2;
## ปุ่มลบข้อมูล
     // เคลียร์ค่าใน Textbox
            num3.Text = "";
            num2.Text = "";
            result.Text = "";