<Type Name="Attachment" FullName="Microsoft.Azure.Documents.Attachment">
  <TypeSignature Language="C#" Value="public class Attachment : Microsoft.Azure.Documents.Resource, System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Attachment extends Microsoft.Azure.Documents.Resource implements class System.Dynamic.IDynamicMetaObjectProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Attachment" />
  <TypeSignature Language="VB.NET" Value="Public Class Attachment&#xA;Inherits Resource&#xA;Implements IDynamicMetaObjectProvider" />
  <TypeSignature Language="F#" Value="type Attachment = class&#xA;    inherit Resource&#xA;    interface IDynamicMetaObjectProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Documents.Resource</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Dynamic.IDynamicMetaObjectProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Dokumentanlage im Azure-Cosmos-DB-Dienst dar.
            </summary>
    <remarks>
            Jedes Dokument kann NULL oder mehr Anlagen, die Daten von beliebigen Formaten wie Bilder, binäres oder großes Text Blobs enthalten. Die Attachment-Klasse stellt die Azure-Cosmos-DB-Ressource, die zum Speichern von Informationen über die Anlage wie sein Speicherort und den MIME-Inhaltstyp verwendet. Die Nutzlast selbst ("Medien") wird über die Eigenschaft "MediaLink" verwiesen. Die Attachment-Klasse ist eine DynamicObject und dürfen benutzerdefinierte Metadaten, die beibehalten werden sollen. 
            
            Anlagen können erstellt werden, als verwaltet oder nicht verwaltet. Wenn Anlagen erstellt werden, als durch Azure Cosmos-Datenbank verwaltet wird, wird er eine vom System generierte "MediaLink" zugewiesen. Azure Cosmos-Datenbank führt dann automatisch Garbagecollection auf dem Medium bei der übergeordneten Dokument gelöscht wird.
            
            Sie können die Eigenschaft "MediaLink" um einen externen Speicherort zu speichern, z. B. eine Dateifreigabe oder eine Azure-Blob-Speicher-URI wiederverwenden. Azure Cosmos-Datenbank wird keine Garbagecollection auf MediaLinks für externen Speicherorten ausführen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Attachment ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Attachment.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der eine <see cref="T:Microsoft.Azure.Documents.Attachment" /> Klasse für den Azure-Cosmos-DB-Dienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Attachment.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.Documents.Attachment.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den MIME-Inhaltstyp der Anlage in der Azure-Cosmos-DB-Dienst.
            </summary>
        <value>
            Der MIME-Inhaltstyp der Anlage.
            </value>
        <remarks>Legen Sie z. B. auf "Text/Plain" für Textdateien, "Image/Jpeg" für Bilder.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaLink">
      <MemberSignature Language="C#" Value="public string MediaLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MediaLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Attachment.MediaLink" />
      <MemberSignature Language="VB.NET" Value="Public Property MediaLink As String" />
      <MemberSignature Language="F#" Value="member this.MediaLink : string with get, set" Usage="Microsoft.Azure.Documents.Attachment.MediaLink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="media")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Medienlink der Inhalt der Anlage in der Azure-Cosmos-Datenbank zugeordnet.
            </summary>
        <value>
            Der Inhalt der Anlage zugeordnete Medienlink.
            </value>
        <remarks>Azure Cosmos-DB unterstützt sowohl verwaltete als auch nicht verwaltete Anlagen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject">
      <MemberSignature Language="C#" Value="System.Dynamic.DynamicMetaObject IDynamicMetaObjectProvider.GetMetaObject (System.Linq.Expressions.Expression parameter);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Dynamic.DynamicMetaObject System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(class System.Linq.Expressions.Expression parameter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Attachment.System#Dynamic#IDynamicMetaObjectProvider#GetMetaObject(System.Linq.Expressions.Expression)" />
      <MemberSignature Language="VB.NET" Value="Function GetMetaObject (parameter As Expression) As DynamicMetaObject Implements IDynamicMetaObjectProvider.GetMetaObject" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Dynamic.IDynamicMetaObjectProvider.GetMetaObject(System.Linq.Expressions.Expression)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Dynamic.DynamicMetaObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameter" Type="System.Linq.Expressions.Expression" />
      </Parameters>
      <Docs>
        <param name="parameter">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>