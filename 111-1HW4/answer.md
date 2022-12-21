# 第4次作業-作業-HW4
>
>學號：109111110 
><br />
>姓名：林育德
><br />
>作業撰寫時間：120(mins，包含程式撰寫時間)
><br />
>最後撰寫文件日期：2022/12/20
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
    ...
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
            <asp:Button ID="Button1" runat="server" Text="點我新增資料" OnClick="Button1_Click" />
            <asp:GridView ID="gd_View" runat="server"></asp:GridView>
        </div>
    </form>
</body>
</html>
```


## 個人認為完成作業須具備觀念



須了解ADO vs. ADO.NET與連接資料庫各個部份的程式寫法
