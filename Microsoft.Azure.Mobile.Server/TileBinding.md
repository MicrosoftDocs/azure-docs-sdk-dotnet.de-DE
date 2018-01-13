<Type Name="TileBinding" FullName="Microsoft.Azure.Mobile.Server.TileBinding">
  <TypeSignature Language="C#" Value="public class TileBinding" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileBinding extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class TileBinding" />
  <TypeSignature Language="F#" Value="type TileBinding = class" />
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
            Diese Klasse stellt die <c>Bindung</c> Element einer Benachrichtigung in der Windows-Kachel, finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> für Details.
            Diese Klasse dient zur Verwendung als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (params Microsoft.Azure.Mobile.Server.TileImage[] images);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileImage[] images) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(Microsoft.Azure.Mobile.Server.TileImage[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray images As TileImage())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : Microsoft.Azure.Mobile.Server.TileImage[] -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding images" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="images" Type="Microsoft.Azure.Mobile.Server.TileImage[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="images">Ein anfänglichen Satz von <see cref="T:Microsoft.Azure.Mobile.Server.TileImage" /> für diese Kachel.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (params Microsoft.Azure.Mobile.Server.TileText[] texts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Mobile.Server.TileText[] texts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(Microsoft.Azure.Mobile.Server.TileText[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray texts As TileText())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : Microsoft.Azure.Mobile.Server.TileText[] -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding texts" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="texts" Type="Microsoft.Azure.Mobile.Server.TileText[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="texts">Ein anfänglichen Satz von <see cref="T:Microsoft.Azure.Mobile.Server.TileText" /> für diese Kachel.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileBinding (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; images, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileText&gt; texts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Mobile.Server.TileImage&gt; images, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Mobile.Server.TileText&gt; texts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileBinding.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Azure.Mobile.Server.TileImage},System.Collections.Generic.IEnumerable{Microsoft.Azure.Mobile.Server.TileText})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (images As IEnumerable(Of TileImage), texts As IEnumerable(Of TileText))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.TileBinding : seq&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; * seq&lt;Microsoft.Azure.Mobile.Server.TileText&gt; -&gt; Microsoft.Azure.Mobile.Server.TileBinding" Usage="new Microsoft.Azure.Mobile.Server.TileBinding (images, texts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="images" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;" />
        <Parameter Name="texts" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Mobile.Server.TileText&gt;" />
      </Parameters>
      <Docs>
        <param name="images">Ein anfänglichen Satz von <see cref="T:Microsoft.Azure.Mobile.Server.TileImage" /> für diese Kachel.</param>
        <param name="texts">Ein anfänglichen Satz von <see cref="T:Microsoft.Azure.Mobile.Server.TileText" /> für diese Kachel.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.TileBinding" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddImageQuery">
      <MemberSignature Language="C#" Value="public bool AddImageQuery { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AddImageQuery" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.AddImageQuery" />
      <MemberSignature Language="VB.NET" Value="Public Property AddImageQuery As Boolean" />
      <MemberSignature Language="F#" Value="member this.AddImageQuery : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.AddImageQuery" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As String" />
      <MemberSignature Language="F#" Value="member this.BaseUri : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.BaseUri" />
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
    <Member MemberName="Branding">
      <MemberSignature Language="C#" Value="public string Branding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Branding" />
      <MemberSignature Language="VB.NET" Value="Public Property Branding As String" />
      <MemberSignature Language="F#" Value="member this.Branding : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Branding" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.ContentId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentId As String" />
      <MemberSignature Language="F#" Value="member this.ContentId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.ContentId" />
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
    <Member MemberName="Fallback">
      <MemberSignature Language="C#" Value="public string Fallback { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fallback" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Fallback" />
      <MemberSignature Language="VB.NET" Value="Public Property Fallback As String" />
      <MemberSignature Language="F#" Value="member this.Fallback : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Fallback" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("fallback")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine Vorlage verwenden, wenn der Name der primären Vorlage vom Empfänger, für die Verwendung mit Windows 8-Kompatibilität nicht erkannt wird. Dieser Wert ist die Windows 8-Namen des Werts in der Vorlagenattribut. Ein Fallback keine neue Vorlagen, die nach dem Windows 8 eingeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt; Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileImage&gt; Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As Collection(Of TileImage)" />
      <MemberSignature Language="F#" Value="member this.Images : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("image")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileImage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine Gruppe von <see cref="T:Microsoft.Azure.Mobile.Server.TileImage" /> Elemente
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Lang" />
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
    <Member MemberName="Template">
      <MemberSignature Language="C#" Value="public string Template { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Template" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Template" />
      <MemberSignature Language="VB.NET" Value="Public Property Template As String" />
      <MemberSignature Language="F#" Value="member this.Template : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Template" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlAttribute("template")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Einer der bereitgestellten Vorlagen auf dem die Kachel basieren. Ein Entwickler muss in der Regel einem Quadrat und einen breiten Format, jeweils als separate Bindungselement bereitgestellt werden. Gültige Einträge sind Member der Enumeration TileTemplateType.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Texts">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt; Texts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.Collection`1&lt;class Microsoft.Azure.Mobile.Server.TileText&gt; Texts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileBinding.Texts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Texts As Collection(Of TileText)" />
      <MemberSignature Language="F#" Value="member this.Texts : System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt;" Usage="Microsoft.Azure.Mobile.Server.TileBinding.Texts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlElement("text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.Collection&lt;Microsoft.Azure.Mobile.Server.TileText&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eine Gruppe von <see cref="T:Microsoft.Azure.Mobile.Server.TileText" /> Elemente
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>