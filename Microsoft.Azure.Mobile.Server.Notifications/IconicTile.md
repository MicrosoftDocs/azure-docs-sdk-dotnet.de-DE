<Type Name="IconicTile" FullName="Microsoft.Azure.Mobile.Server.Notifications.IconicTile">
  <TypeSignature Language="C#" Value="public class IconicTile : Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IconicTile extends Microsoft.Azure.Mobile.Server.Notifications.MpnsTileMessage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />
  <TypeSignature Language="VB.NET" Value="Public Class IconicTile&#xA;Inherits MpnsTileMessage" />
  <TypeSignature Language="F#" Value="type IconicTile = class&#xA;    inherit MpnsTileMessage" />
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
            <span data-ttu-id="a8fb0-101">Stellt eine Elementsymbol Kachel Zielgruppenadressierung MPNS dar.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-101">Represents a Iconic Tile targeting MPNS.</span></span> <span data-ttu-id="a8fb0-102">Verwenden der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> mit <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> MPNS-Benachrichtigung erstellen und senden es mithilfe der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-102">Use the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> with <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> to create an MPNS notification and send it using the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.PushClient" />.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="a8fb0-103">Weitere Informationen zu MPNS Elementsymbol Kacheln finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj207009</c>.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-103">For more information about MPNS Iconic Tiles, see <c>http://msdn.microsoft.com/en-us/library/windowsphone/develop/jj207009</c>.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IconicTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a8fb0-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-104">Initialize a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.IconicTile" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackgroundColor">
      <MemberSignature Language="C#" Value="public string BackgroundColor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackgroundColor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.BackgroundColor" />
      <MemberSignature Language="VB.NET" Value="Public Property BackgroundColor As String" />
      <MemberSignature Language="F#" Value="member this.BackgroundColor : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.BackgroundColor" />
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
            <span data-ttu-id="a8fb0-105">Ruft ab oder legt die Hintergrundfarbe der Kachel fest.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-105">Gets or sets the background color of the Tile.</span></span> <span data-ttu-id="a8fb0-106">Diese Einstellung überschreibt die Standardfarbe für das Design, die auf dem Telefon festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-106">Setting this property overrides the default theme color that is set on the phone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IconImage">
      <MemberSignature Language="C#" Value="public Uri IconImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri IconImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.IconImage" />
      <MemberSignature Language="VB.NET" Value="Public Property IconImage As Uri" />
      <MemberSignature Language="F#" Value="member this.IconImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.IconImage" />
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
            <span data-ttu-id="a8fb0-107">Ruft ab oder legt das Symbolbild für die mittelgroßen und großen kachelgrößen.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-107">Gets or sets the icon image for the medium and large tile sizes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SmallIconImage">
      <MemberSignature Language="C#" Value="public Uri SmallIconImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri SmallIconImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.SmallIconImage" />
      <MemberSignature Language="VB.NET" Value="Public Property SmallIconImage As Uri" />
      <MemberSignature Language="F#" Value="member this.SmallIconImage : Uri with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.SmallIconImage" />
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
            <span data-ttu-id="a8fb0-108">Ruft ab oder legt das Symbolbild für die Größe der kleinen Kachel.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-108">Gets or sets the icon image for the small tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent1">
      <MemberSignature Language="C#" Value="public string WideContent1 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent1" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent1" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent1 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent1 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent1" />
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
            <span data-ttu-id="a8fb0-109">Ruft ab oder legt den Text, der auf die erste Zeile der Kachelgröße wide angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-109">Gets or sets the text that displays on the first row of the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent2">
      <MemberSignature Language="C#" Value="public string WideContent2 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent2" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent2 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent2 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent2" />
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
            <span data-ttu-id="a8fb0-110">Ruft ab oder legt den Text, der auf der zweiten Zeile, der die Breite Kachelgröße anzeigt.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-110">Gets or sets the text that displays on the second row of the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WideContent3">
      <MemberSignature Language="C#" Value="public string WideContent3 { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WideContent3" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent3" />
      <MemberSignature Language="VB.NET" Value="Public Property WideContent3 As String" />
      <MemberSignature Language="F#" Value="member this.WideContent3 : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.IconicTile.WideContent3" />
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
            <span data-ttu-id="a8fb0-111">Ruft ab oder legt den Text, der auf der dritten Zeile von der Breite Kachelgröße anzeigt.</span><span class="sxs-lookup"><span data-stu-id="a8fb0-111">Gets or sets the text that displays on the third row of the wide tile size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>