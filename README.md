
# EN_Library

A simple library of pre-designed notifications


## Example code

Sample code how to use the library

```csharp
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;
using EN_Library;
using EN_Library.Forms;


namespace EN_Library_Sample
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        public Notifications notification = new Notifications();
        private void successBtn_Click(object sender, EventArgs e)
        {
            notification.Notification("Success Notification!", Frm_Notification.enmType.Success);
        }

        private void informationBtn_Click(object sender, EventArgs e)
        {
            notification.Notification("Information Notification!", Frm_Notification.enmType.Info);
        }

        private void warningBtn_Click(object sender, EventArgs e)
        {
            notification.Notification("Warning Notification!", Frm_Notification.enmType.Warning);
        }

        private void errorBtn_Click(object sender, EventArgs e)
        {
            notification.Notification("Error Notification!", Frm_Notification.enmType.Error);
        }
    }
}
  
```


# Preview


![success notification](https://raw.githubusercontent.com/lulv3z/EN_Library/main/img/success.png)


![information notification](https://raw.githubusercontent.com/lulv3z/EN_Library/main/img/info.png)


![warning notification](https://raw.githubusercontent.com/lulv3z/EN_Library/main/img/warning.png)


![error notification](https://raw.githubusercontent.com/lulv3z/EN_Library/main/img/error.png)

