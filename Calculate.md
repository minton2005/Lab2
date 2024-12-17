namespace Calculate
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button3_Click(object sender, EventArgs e)
        {
            // ข้อความตัวอักษร
            string inputNum1 = num1.Text;
            string inputNum2 = num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 - iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            result.Text = iResult.ToString();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            string inputNum1 = num1.Text;
            string inputNum2 = num2.Text;
            //convert string to number (integer)
            // int => integer => เลขจำนวนเต็ม
            // double /  float => เลขทศนิยม
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);

            int iResult = iNum1 + iNum2;
            //ที่ตัวแปรชื่อ result
            //มีคุณสมบัติชื่อ Text
            result.Text = iResult.ToString();

        }

        private void button2_Click(object sender, EventArgs e)
        {
            // ข้อความตัวอักษร
            string inputNum1 = num1.Text;
            string inputNum2 = num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 * iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            result.Text = iResult.ToString();
        }

        private void button4_Click(object sender, EventArgs e)
        {
            // ข้อความตัวอักษร
            string inputNum1 = num1.Text;
            string inputNum2 = num2.Text;
            // convert string to number (integer)
            int iNum1 = Int32.Parse(inputNum1);
            int iNum2 = Int32.Parse(inputNum2);
            // int ทำให้เราสามารถทำการ + - * / ได้
            int iResult = iNum1 / iNum2;
            // ที่ตัวแปรชื่อ result
            // มีคุณสมบัติชื่อ Text
            result.Text = iResult.ToString();
        }

        private void button5_Click(object sender, EventArgs e)
        {
            num1.Text = "";
            num2.Text = "";
            result.Text = "";
        }
    }
}
