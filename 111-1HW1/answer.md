# 第1次作業-作業-HW1
>
>學號：109111139
><br />
>姓名：繆昊廷 
><br />
>作業撰寫時間：20+
><br />
>最後撰寫文件日期：2022/10/12
>

本份文件包含以下主題：(至少需下面兩項，若是有多者可以自行新增)
- [x]說明內容
- [x]個人認為完成作業須具備觀念

## 說明程式與內容


下段程式碼則為使用後結果：顯示Hello App字串，當按鈕按下時，顯示Hello Button字串

```csharp
protected void Page_Load(object sender, EventArgs e)
        {
            Response.Write("Hello App");
        }

        protected void Button1_Click(object sender, EventArgs e)
        {
            Response.Write("Hello Button");
        }
```


下段程式碼則為使用後結果：顯示按鈕

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
        <asp:Button ID="btn_Show" runat="server" Text="Button" OnClick="Button1_Click" />
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念


需要學會用Response.Write，這個就是用來顯示字串的，以及按鈕是可以拖曳到程式碼上的，如果要在按鈕上寫程式的話，要連點按鈕兩次。

