﻿# 第3次隨堂-隨堂-QZ3
>
>學號：1234567 
><br />
>姓名：王小明 
><br />
>作業撰寫時間：180 (mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/10/12
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容

開始寫說明，該說明需說明想法，
並於之後再對上述想法的每一部分將程式進一步進行展現，
若需引用程式區則使用下面方法，
若為.cs檔內程式除了於敘述中需註明檔案名稱外，
還需使用語法` ```csharp 程式碼 ``` `，
下段程式碼則為使用後結果：

```csharp
public void mt_getResult(){
    string[] s_city = new string[3](“台北市”, "新北市”,“台中市”};
            string[,] s_Area = new string[3, 3] {
            {“中正區”,“文山區”, "大安區”},
            { “淡水區”,“石碇區”,“土城區”},
            { “西屯區”,“北屯區”,“東區”}
            };
            protected void Page_Load(object sender, EventArgs e)
            {
                if (!IsPostBack)
                {
                    for (int i_Ct = 0; i_ct < s_City.Length; i_Ct++)
                    { }
                    ListItem a_C = new ListItem();
                    a_C.Text = a_C.Value = s_City[i_ct];
                    dpl_City.Items.Add(a_C);
                }
            }
            if (rbl_Phone.Text = = "無")
                txt_Phone.Visible = false;
        }
            else
            {
             txt_Phone.Visible = true; ;
            }
}
            protected System.Void dpl_City_SelectedIndexChanged(System.Object sender,
            mt_GenSecondList();
            protected void mt_GenSecondList()
            int i_ind = dpl_city.SelectedIndex;
            dp1_Area.Items.clear();
for (int i_ct = 0; i_ct < s_Area.GetLength(0); i_ct++)
{
    ListItem a_C = new ListItem();
    a_c.Text = a_C.Value = s_Area[i_ind, i_ct];

    dp1_Area.Items.Add(a_C);
}
}
}
public partial class Test_Sub : System.Web.UI.Page
protected void Page_Load(object sender, EventArgs e)
{
    { 
if (Request.Form,Get("rbl_Phone") == "無")
{ 
16_Msg.Text = ("尽單編號:“)+Request.Form.Get("tb_Num ")+(" < l
}
else
{ 
    1b_MsB.Text = ("保單編號:“)+Request.Form.Get("tb_Num ")+(“<I

           


        }
}
}
}
```

若要於內文中標示部分.aspx檔，則使用以下標籤` ```html 程式碼 ``` `，
下段程式碼則為使用後結果：

```html
<%@ Page Language="C#" AutoEventWireup="true" ...>

<!DOCTYPE html>

<html xmlns="http://www.w3.org/1999/xhtml">
<head runat="server">
<meta http-equiv="Content-Type" ...>
    <title></title>
</head>
<body>
    <form id="form1" runat="server">
        <div>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念

開始寫說明，需要說明本次作業個人覺得需學會那些觀念 (需寫成文章，需最少50字，
並且文內不得有你、我、他三種文字)

