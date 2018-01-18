<Type Name="FlipTile" FullName="Microsoft.Azure.Mobile.Server.Notifications.FlipTile">
  <TypeSignature Language="C#" Value="public class FlipTile : Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FlipTile extends Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />
  <TypeSignature Language="VB.NET" Value="Public Class FlipTile&#xA;Inherits MpnsTileMessage" />
  <TypeSignature Language="F#" Value="type FlipTile = class&#xA;    inherit MpnsTileMessage" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="26cf1-101">Stellt eine Flip Tile Zielgruppenadressierung MPNS dar.</span><span class="sxs-lookup"><span data-stu-id="26cf1-101">Represents a Flip Tile targeting MPNS.</span></span> <span data-ttu-id="26cf1-102">Verwenden der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" /> mit <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> MPNS-Benachrichtigung erstellen und senden es mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span><span class="sxs-lookup"><span data-stu-id="26cf1-102">Use the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" /> with <see cref="T:Microsoft.Azure.Mobile.Server.MpnsPushMessage" /> to create an MPNS notification and send it using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="26cf1-103">Weitere Informationen zu MPNS kippen Kacheln finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj206971</c>.</span><span class="sxs-lookup"><span data-stu-id="26cf1-103">For more information about MPNS Flip Tiles, see <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj206971</c>.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FlipTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26cf1-104">Initialize a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.FlipTile" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackBackgroundImage">
      <MemberSignature Language="C#" Value="public Uri BackBackgroundImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BackBackgroundImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackBackgroundImage" />
      <MemberSignature Language="VB.NET" Value="Public Property BackBackgroundImage As Uri" />
      <MemberSignature Language="F#" Value="member this.BackBackgroundImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackBackgroundImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-105">Ruft ab oder legt ein Hintergrundbild der Rückseite der Kachel fest.</span><span class="sxs-lookup"><span data-stu-id="26cf1-105">Gets or sets a background image of the back of the tile.</span></span> <span data-ttu-id="26cf1-106">Wenn diese Eigenschaft ein leerer URI zugelassen ist, wird das Hintergrundbild der Rückseite der Kachel während einer Aktualisierung nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="26cf1-106">If this property is an empty URI, the background image of the back of the tile will not change during an update.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackContent">
      <MemberSignature Language="C#" Value="public string BackContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackContent" />
      <MemberSignature Language="VB.NET" Value="Public Property BackContent As String" />
      <MemberSignature Language="F#" Value="member this.BackContent : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-107">Ruft ab oder legt den Text auf der Rückseite der Kachel, über den Titel angezeigt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="26cf1-107">Gets or sets the text to display on the back of the tile, above the title.</span></span> <span data-ttu-id="26cf1-108">Wenn diese Eigenschaft eine leere Zeichenfolge ist, ändert sich der Inhalt auf der Rückseite der Kachel während einer Aktualisierung nicht.</span><span class="sxs-lookup"><span data-stu-id="26cf1-108">If this property is an empty string, the content on the back of the tile will not change during an update.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackgroundImage">
      <MemberSignature Language="C#" Value="public Uri BackgroundImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BackgroundImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackgroundImage" />
      <MemberSignature Language="VB.NET" Value="Public Property BackgroundImage As Uri" />
      <MemberSignature Language="F#" Value="member this.BackgroundImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackgroundImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-109">Ruft ab oder legt das Hintergrundbild für den Anfang der Kachel fest.</span><span class="sxs-lookup"><span data-stu-id="26cf1-109">Gets or sets the background image of the front of the tile.</span></span> <span data-ttu-id="26cf1-110">Wenn diese Eigenschaft ein leerer URI zugelassen ist, wird das Hintergrundbild des den vorderen Teil der Kachel während einer Aktualisierung nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="26cf1-110">If this property is an empty URI, the background image of the front of the tile will not change during an update.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackTitle">
      <MemberSignature Language="C#" Value="public string BackTitle { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackTitle" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackTitle" />
      <MemberSignature Language="VB.NET" Value="Public Property BackTitle As String" />
      <MemberSignature Language="F#" Value="member this.BackTitle : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.BackTitle" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-111">Ermittelt oder definiert den Titel, der am unteren Rand der Rückseite der Kachel angezeigt.</span><span class="sxs-lookup"><span data-stu-id="26cf1-111">Gets or sets the title to display at the bottom of the back of the tile.</span></span> <span data-ttu-id="26cf1-112">Wenn diese Eigenschaft eine leere Zeichenfolge ist, wird der Titel auf der Rückseite der Kachel während einer Aktualisierung nicht geändert.</span><span class="sxs-lookup"><span data-stu-id="26cf1-112">If this property is an empty string, the title on the back of the tile will not change during an update.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SmallBackgroundImage">
      <MemberSignature Language="C#" Value="public Uri SmallBackgroundImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SmallBackgroundImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.SmallBackgroundImage" />
      <MemberSignature Language="VB.NET" Value="Public Property SmallBackgroundImage As Uri" />
      <MemberSignature Language="F#" Value="member this.SmallBackgroundImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.SmallBackgroundImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-113">Ermittelt und die Vorderseite Hintergrundbild für die kleine Größe definiert.</span><span class="sxs-lookup"><span data-stu-id="26cf1-113">Gets and sets the front-side background image for the small tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideBackBackgroundImage">
      <MemberSignature Language="C#" Value="public Uri WideBackBackgroundImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri WideBackBackgroundImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackBackgroundImage" />
      <MemberSignature Language="VB.NET" Value="Public Property WideBackBackgroundImage As Uri" />
      <MemberSignature Language="F#" Value="member this.WideBackBackgroundImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackBackgroundImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-114">Ruft ab und legt das Hintergrundbild für Back-Seite für die Breite Kachelgröße fest.</span><span class="sxs-lookup"><span data-stu-id="26cf1-114">Gets and sets the back-side background image for the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideBackContent">
      <MemberSignature Language="C#" Value="public string WideBackContent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideBackContent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackContent" />
      <MemberSignature Language="VB.NET" Value="Public Property WideBackContent As String" />
      <MemberSignature Language="F#" Value="member this.WideBackContent : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackContent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-115">Ermittelt und definiert den Text, der über den Titel auf der Back-Seite von der Breite Kachelgröße anzeigt.</span><span class="sxs-lookup"><span data-stu-id="26cf1-115">Gets and sets the text that displays above the title, on the back-side of the wide tile size.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideBackgroundImage">
      <MemberSignature Language="C#" Value="public Uri WideBackgroundImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri WideBackgroundImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackgroundImage" />
      <MemberSignature Language="VB.NET" Value="Public Property WideBackgroundImage As Uri" />
      <MemberSignature Language="F#" Value="member this.WideBackgroundImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.FlipTile.WideBackgroundImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cf1-116">Ermittelt und definiert die Vorderseite Hintergrundbild für die Breite Kachelgröße.</span><span class="sxs-lookup"><span data-stu-id="26cf1-116">Gets and sets the front-side background image for the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>