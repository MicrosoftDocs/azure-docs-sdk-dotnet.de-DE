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
            Diese Klasse stellt die <c>Image</c> Element einer Benachrichtigung in der Windows-Kachel, finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> für Details.
            Diese Klasse dient zur Verwendung als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Klasse.
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
            Legen Sie auf "true", ermöglichen Windows, auf das Abbild in den Tile-Benachrichtigung angegebene URI eine Abfragezeichenfolge angefügt werden soll. Verwenden Sie dieses Attribut aus, wenn Ihr Server Bilder hostet und Abfragezeichenfolgen behandeln kann, durch das Abrufen von eine Bild-Variante, die basierend auf den Abfragezeichenfolgen oder durch Ignorieren der Abfragezeichenfolge und das Bild entsprechend den Angaben, ohne die Abfragezeichenfolge zurückgeben. Dieser Abfragezeichenfolge gibt an, Skalierung, kontrasteinstellung und Sprache. z. B. einen Wert von <c>www.website.com/images/hello.png</c> der Benachrichtigung wird <c>www.website.com/images/hello.png?ms-scale=100&amp;ms Kontrast = Standard&amp; MS-Lang = En-us</c>.
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
            Eine Beschreibung des Bilds für Benutzer von hilfstechnologien.
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
            Das Image-Element in der Tile-Vorlage, der für dieses Image vorgesehen ist. Wenn eine Vorlage nur ein Bild verfügt, ist dieser Wert 1. Die Anzahl der verfügbaren Image basiert auf der Vorlagendefinition.
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
            Der URI des Bilds-Datenquelle, eine der folgenden Protokollhandler: <c>http://</c> oder <c>https://</c> bedeutet, dass ein Image webbasierte <c>ms-Appx: / / /</c> bedeutet, dass ein Bild in das app-Paket enthalten <c>ms Appdata: / / / lokal/</c> bedeutet, dass ein Bild in den lokalen Speicher gespeichert und <c>file:///</c> bedeutet, dass ein lokales Bild. (Nur für desktop-apps unterstützt. Dieses Protokoll kann nicht von Windows Store-apps verwendet werden.)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>