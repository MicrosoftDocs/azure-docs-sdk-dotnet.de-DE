<Type Name="VisualTile" FullName="Microsoft.Azure.Mobile.Server.Notifications.VisualTile">
  <TypeSignature Language="C#" Value="public class VisualTile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VisualTile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />
  <TypeSignature Language="VB.NET" Value="Public Class VisualTile" />
  <TypeSignature Language="F#" Value="type VisualTile = class" />
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
            Diese Klasse stellt die <c>visual</c> Element einer Benachrichtigung in der Windows-Kachel, finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> für Details.
            Diese Klasse dient zur Verwendung als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VisualTile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VisualTile (params Microsoft.Azure.Mobile.Server.TileBinding[] bindings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileBinding[] bindings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.#ctor(Microsoft.Azure.Mobile.Server.TileBinding[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray bindings As TileBinding())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Notifications.VisualTile : Microsoft.Azure.Mobile.Server.TileBinding[] -&gt; Microsoft.Azure.Mobile.Server.Notifications.VisualTile" Usage="new Microsoft.Azure.Mobile.Server.Notifications.VisualTile bindings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="bindings" Type="Microsoft.Azure.Mobile.Server.TileBinding[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="bindings">Einen anfänglichen Satz von Bindungen für diesen <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Notifications.VisualTile" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.AddImageQuery" />
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
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public string BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As String" />
      <MemberSignature Language="F#" Value="member this.BaseUri : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1056:UriPropertiesShouldNotBeStrings", Justification="XmlSerializer doesn't handle System.Uri")</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("baseUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine standardmäßige Basis-URI, der mit relativen URIs in Quelle Bildattributen kombiniert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bindings">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt; Bindings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileBinding&gt; Bindings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Bindings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Bindings As Collection(Of TileBinding)" />
      <MemberSignature Language="F#" Value="member this.Bindings : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt;" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Bindings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("binding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileBinding&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" /> gibt eine Kachel Vorlagen an. Jede Benachrichtigung sollte ein Bindungselement für jeden unterstützten Kachelgröße enthalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Branding">
      <MemberSignature Language="C#" Value="public string Branding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Branding" />
      <MemberSignature Language="VB.NET" Value="Public Property Branding As String" />
      <MemberSignature Language="F#" Value="member this.Branding : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Branding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("branding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Formular, das die Kachel verwenden soll, um die app Brand anzuzeigen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentId">
      <MemberSignature Language="C#" Value="public string ContentId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.ContentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentId As String" />
      <MemberSignature Language="F#" Value="member this.ContentId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.ContentId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("contentId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legen Sie auf eine Absender benutzerdefinierte Zeichenfolge, die den Inhalt der Benachrichtigung eindeutig identifiziert. Dies verhindert, dass alle Duplikate in der Lage, in denen eine große Tile-Vorlage für die letzten drei wide Tile-Benachrichtigungen angezeigt wird. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Lang" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("lang")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Zielgebietsschema des der XML-Nutzlast angegeben, wie eine Sprache für die BCP-47-wie Tags <c>En-US</c> oder <c>fr-FR</c>. Das hier angegebene Gebietsschema überschreibt andere angegebene Gebietsschema, z. B., dass in der Bindung oder das visuelle. Wenn dieser Wert eine literale Zeichenfolge ist, standardmäßig dieses Attribut Benutzeroberflächensprache des Benutzers. Wenn dieser Wert einen Zeichenfolgenverweis ist, verwendet dieses Attribut standardmäßig das Gebietsschema, das von Windows-Runtime gewählt wird, bei der Behebung von der Zeichenfolge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public int Version { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Version" />
      <MemberSignature Language="VB.NET" Value="Public Property Version As Integer" />
      <MemberSignature Language="F#" Value="member this.Version : int with get, set" Usage="Microsoft.Azure.Mobile.Server.Notifications.VisualTile.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DefaultValue(1)</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Version der Kachel XML-Schema wurde für diese bestimmte Nutzlast entwickelt. Verfügen sie über zwei Werte, 1 oder 2. Version 1 erfordert eine gültige Nutzlast unter Windows 8-Schema. Version 2 erkennt die neuen Vorlagen mit großen Kachel, der neuen Vorlage für Windows 8.1 Namen vorhandener Vorlagen und das fallback-Attribut des Bindungselements.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>