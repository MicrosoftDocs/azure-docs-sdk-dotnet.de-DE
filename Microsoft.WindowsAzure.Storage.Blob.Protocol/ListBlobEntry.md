<Type Name="ListBlobEntry" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry">
  <TypeSignature Language="C#" Value="public sealed class ListBlobEntry : Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlobEntry extends System.Object implements class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlobEntry&#xA;Implements IListBlobEntry" />
  <TypeSignature Language="F#" Value="type ListBlobEntry = class&#xA;    interface IListBlobEntry" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt ein Blob-Element, das in der XML-Antwort für eine Blob-Auflistungsvorgang zurückgegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyState">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.CopyState CopyState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyState As CopyState" />
      <MemberSignature Language="F#" Value="member this.CopyState : Microsoft.WindowsAzure.Storage.Blob.CopyState" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.CopyState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des letzten oder ausstehenden Kopiervorgangs ab.
            </summary>
        <value>Ein <see cref="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.CopyState" /> Objekt, das den Kopierstatus enthält oder <c>null</c> Wenn kein kopierzustand für das Blob für dieses Blob vorhanden ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Metadata { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metadata As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die benutzerdefinierten Metadaten für das Blob-Element ab.
            </summary>
        <value>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Blob-Element-Metadaten als eine Auflistung von Name / Wert-Paaren enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des BLOB-Elements ab.
            </summary>
        <value>Eine Zeichenfolge, die mit dem Namen des BLOB-Elements.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As BlobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.WindowsAzure.Storage.Blob.BlobProperties" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Blob-Systemeigenschaften des Elements ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobProperties" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SnapshotTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SnapshotTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SnapshotTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.SnapshotTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SnapshotTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SnapshotTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.SnapshotTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Datum und die Uhrzeit, zu der die Blob-Momentaufnahme erstellt wurde, ab, wenn dieses Blob eine Momentaufnahme ist.
            </summary>
        <value>Momentaufnahmezeit des BLOBs, wenn das Blob eine Momentaufnahme ist; andernfalls <c>null</c>.</value>
        <remarks>
            Wenn das Blob keine Momentaufnahme ist, ist der Wert dieser Eigenschaft <c>null</c>.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobEntry.Uri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Blob-Element-URI ab.
            </summary>
        <value>Der absolute URI zum BLOB-Element.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>