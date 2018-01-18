<Type Name="TileImage" FullName="Microsoft.Azure.Mobile.Server.TileImage">
  <TypeSignature Language="C#" Value="public class TileImage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileImage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileImage" />
  <TypeSignature Language="VB.NET" Value="Public Class TileImage" />
  <TypeSignature Language="F#" Value="type TileImage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d31d2-101">Diese Klasse stellt die <c>Image</c> Element einer Benachrichtigung in der Windows-Kachel, finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> für Details.</span><span class="sxs-lookup"><span data-stu-id="d31d2-101">This class represents the <c>image</c> element of a Windows Notification tile, see <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> for details.</span></span>
            <span data-ttu-id="d31d2-102">Diese Klasse dient zur Verwendung als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="d31d2-102">This class is intended for use as part of the <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileImage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.AddImageQuery" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(false)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("addImageQuery")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31d2-103">Legen Sie auf "true", ermöglichen Windows, auf das Abbild in den Tile-Benachrichtigung angegebene URI eine Abfragezeichenfolge angefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="d31d2-103">Set to true to allow Windows to append a query string to the image URI supplied in the tile notification.</span></span> <span data-ttu-id="d31d2-104">Verwenden Sie dieses Attribut aus, wenn Ihr Server Bilder hostet und Abfragezeichenfolgen behandeln kann, durch das Abrufen von eine Bild-Variante, die basierend auf den Abfragezeichenfolgen oder durch Ignorieren der Abfragezeichenfolge und das Bild entsprechend den Angaben, ohne die Abfragezeichenfolge zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="d31d2-104">Use this attribute if your server hosts images and can handle query strings, either by retrieving an image variant based on the query strings or by ignoring the query string and returning the image as specified without the query string.</span></span> <span data-ttu-id="d31d2-105">Dieser Abfragezeichenfolge gibt an, Skalierung, kontrasteinstellung und Sprache. z. B. einen Wert von <c>www.website.com/images/hello.png</c> der Benachrichtigung wird <c>www.website.com/images/hello.png?ms-scale=100&amp;ms Kontrast = Standard&amp; MS-Lang = En-us</c>.</span><span class="sxs-lookup"><span data-stu-id="d31d2-105">This query string specifies scale, contrast setting, and language; for instance, a value of <c>www.website.com/images/hello.png</c> included in the notification becomes <c>www.website.com/images/hello.png?ms-scale=100&amp;ms-contrast=standard&amp;ms-lang=en-us</c>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Alt">
      <MemberSignature Language="C#" Value="public string Alt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Alt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Alt" />
      <MemberSignature Language="VB.NET" Value="Public Property Alt As String" />
      <MemberSignature Language="F#" Value="member this.Alt : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Alt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("alt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31d2-106">Eine Beschreibung des Bilds für Benutzer von hilfstechnologien.</span><span class="sxs-lookup"><span data-stu-id="d31d2-106">A description of the image, for users of assistive technologies.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public int Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Integer" />
      <MemberSignature Language="F#" Value="member this.Id : int with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31d2-107">Das Image-Element in der Tile-Vorlage, der für dieses Image vorgesehen ist.</span><span class="sxs-lookup"><span data-stu-id="d31d2-107">The image element in the tile template that this image is intended for.</span></span> <span data-ttu-id="d31d2-108">Wenn eine Vorlage nur ein Bild verfügt, ist dieser Wert 1.</span><span class="sxs-lookup"><span data-stu-id="d31d2-108">If a template has only one image, then this value is 1.</span></span> <span data-ttu-id="d31d2-109">Die Anzahl der verfügbaren Image basiert auf der Vorlagendefinition.</span><span class="sxs-lookup"><span data-stu-id="d31d2-109">The number of available image positions is based on the template definition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Src">
      <MemberSignature Language="C#" Value="public string Src { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Src" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileImage.Src" />
      <MemberSignature Language="VB.NET" Value="Public Property Src As String" />
      <MemberSignature Language="F#" Value="member this.Src : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileImage.Src" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("src")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31d2-110">Der URI des Bilds-Datenquelle, eine der folgenden Protokollhandler: <c>http://</c> oder <c>https://</c> bedeutet, dass ein Image webbasierte <c>ms-Appx: / / /</c> bedeutet, dass ein Bild in das app-Paket enthalten <c>ms Appdata: / / / lokal/</c> bedeutet, dass ein Bild in den lokalen Speicher gespeichert und <c>file:///</c> bedeutet, dass ein lokales Bild.</span><span class="sxs-lookup"><span data-stu-id="d31d2-110">The URI of the image source, one of these protocol handlers: <c>http://</c> or <c>https://</c> means a web-based image, <c>ms-appx:///</c> means an image included in the app package, <c>ms-appdata:///local/</c> means an image saved to local storage, and <c>file:///</c> means a local image.</span></span> <span data-ttu-id="d31d2-111">(Nur für desktop-apps unterstützt.</span><span class="sxs-lookup"><span data-stu-id="d31d2-111">(Supported only for desktop apps.</span></span> <span data-ttu-id="d31d2-112">Dieses Protokoll kann nicht von Windows Store-apps verwendet werden.)</span><span class="sxs-lookup"><span data-stu-id="d31d2-112">This protocol cannot be used by Windows Store apps.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>