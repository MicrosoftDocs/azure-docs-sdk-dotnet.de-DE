<Type Name="TileText" FullName="Microsoft.Azure.Mobile.Server.TileText">
  <TypeSignature Language="C#" Value="public class TileText" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TileText extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.TileText" />
  <TypeSignature Language="VB.NET" Value="Public Class TileText" />
  <TypeSignature Language="F#" Value="type TileText = class" />
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
            Diese Klasse stellt die <c>Text</c> Element einer Benachrichtigung in der Windows-Kachel, finden Sie unter <c>http://msdn.microsoft.com/en-us/library/windows/apps/hh761491.aspx</c> für Details.
            Diese Klasse dient zur Verwendung als Teil der <see cref="T:Microsoft.Azure.Mobile.Server.WindowsPushMessage" /> Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TileText ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.TileText.#ctor" />
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
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public int Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Integer" />
      <MemberSignature Language="F#" Value="member this.Id : int with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Id" />
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
            Das Textelement in der Tile-Vorlage, der für diesen Text vorgesehen ist. Wenn eine Vorlage nur ein Textelement verfügt, ist dieser Wert 1. Die Anzahl der verfügbaren Text-Positionen basiert auf der Vorlagendefinition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lang">
      <MemberSignature Language="C#" Value="public string Lang { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Lang" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Lang" />
      <MemberSignature Language="VB.NET" Value="Public Property Lang As String" />
      <MemberSignature Language="F#" Value="member this.Lang : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Lang" />
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
    <Member MemberName="Text">
      <MemberSignature Language="C#" Value="public string Text { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Text" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.TileText.Text" />
      <MemberSignature Language="VB.NET" Value="Public Property Text As String" />
      <MemberSignature Language="F#" Value="member this.Text : string with get, set" Usage="Microsoft.Azure.Mobile.Server.TileText.Text" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Notifications</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Xml.Serialization.XmlText</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der tatsächliche Text des Elements Kachel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>