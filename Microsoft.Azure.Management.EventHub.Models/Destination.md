<Type Name="Destination" FullName="Microsoft.Azure.Management.EventHub.Models.Destination">
  <TypeSignature Language="C#" Value="public class Destination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Destination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.Destination" />
  <TypeSignature Language="VB.NET" Value="Public Class Destination" />
  <TypeSignature Language="F#" Value="type Destination = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erfassen von Speicherdetails Capture-Beschreibung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.Destination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Ziel-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination (string name = null, string storageAccountResourceId = null, string blobContainer = null, string archiveNameFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string storageAccountResourceId, string blobContainer, string archiveNameFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.Destination.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional storageAccountResourceId As String = null, Optional blobContainer As String = null, Optional archiveNameFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.Destination : string * string * string * string -&gt; Microsoft.Azure.Management.EventHub.Models.Destination" Usage="new Microsoft.Azure.Management.EventHub.Models.Destination (name, storageAccountResourceId, blobContainer, archiveNameFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageAccountResourceId" Type="System.String" />
        <Parameter Name="blobContainer" Type="System.String" />
        <Parameter Name="archiveNameFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Namen für die Erfassung-Ziel</param>
        <param name="storageAccountResourceId">Ressourcen-Id des Speicherkontos verwendet werden, um die Blobs zu erstellen.</param>
        <param name="blobContainer">Name des BLOB-container</param>
        <param name="archiveNameFormat">BLOB-Benennungskonvention für die Archivierung, z. B. {Namespace} / {EventHub} / {PartitionId} / {Year} / {Month} / {Day} / {Stunde} / {Minute} / {Sekunde}.
            Hier alle Parameter ("Namespace", "EventHub".. usw.) müssen unabhängig von der Reihenfolge angegeben werden</param>
        <summary>
            Initialisiert eine neue Instanz der Ziel-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ArchiveNameFormat">
      <MemberSignature Language="C#" Value="public string ArchiveNameFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ArchiveNameFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.Destination.ArchiveNameFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property ArchiveNameFormat As String" />
      <MemberSignature Language="F#" Value="member this.ArchiveNameFormat : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.Destination.ArchiveNameFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.archiveNameFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-BLOB-Benennungskonvention für die Archivierung, z. B. {Namespace} / {EventHub} / {PartitionId} / {Year} / {Month} / {Day} / {Stunde} / {Minute} / {Sekunde}.
            Hier alle Parameter ("Namespace", "EventHub".. usw.) müssen unabhängig von der Reihenfolge angegeben werden
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobContainer">
      <MemberSignature Language="C#" Value="public string BlobContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.Destination.BlobContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobContainer As String" />
      <MemberSignature Language="F#" Value="member this.BlobContainer : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.Destination.BlobContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-Blob-Container namens
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.Destination.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.Destination.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest für Capture-Ziel
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountResourceId">
      <MemberSignature Language="C#" Value="public string StorageAccountResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.Destination.StorageAccountResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountResourceId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountResourceId : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.Destination.StorageAccountResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Ressourcen-Id des Speicherkontos verwendet werden, um die Blobs zu erstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>