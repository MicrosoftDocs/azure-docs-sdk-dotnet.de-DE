<Type Name="Destination" FullName="Microsoft.Azure.Management.ServiceBus.Models.Destination">
  <TypeSignature Language="C#" Value="public class Destination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Destination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Destination" />
  <TypeSignature Language="VB.NET" Value="Public Class Destination" />
  <TypeSignature Language="F#" Value="type Destination = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22108-101">Erfassen von Speicherdetails Capture-Beschreibung</span><span class="sxs-lookup"><span data-stu-id="22108-101">Capture storage details for capture description</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Destination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22108-102">Initialisiert eine neue Instanz der Ziel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22108-102">Initializes a new instance of the Destination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Destination (string name = null, string storageAccountResourceId = null, string blobContainer = null, string archiveNameFormat = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string storageAccountResourceId, string blobContainer, string archiveNameFormat) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Destination.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional storageAccountResourceId As String = null, Optional blobContainer As String = null, Optional archiveNameFormat As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Destination : string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.Destination" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Destination (name, storageAccountResourceId, blobContainer, archiveNameFormat)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageAccountResourceId" Type="System.String" />
        <Parameter Name="blobContainer" Type="System.String" />
        <Parameter Name="archiveNameFormat" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="22108-103">Namen für die Erfassung-Ziel</span><span class="sxs-lookup"><span data-stu-id="22108-103">Name for capture destination</span></span></param>
        <param name="storageAccountResourceId"><span data-ttu-id="22108-104">Ressourcen-Id des Speicherkontos verwendet werden, um die Blobs zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="22108-104">Resource id of the storage account to be used to create the blobs</span></span></param>
        <param name="blobContainer"><span data-ttu-id="22108-105">Name des BLOB-container</span><span class="sxs-lookup"><span data-stu-id="22108-105">Blob container Name</span></span></param>
        <param name="archiveNameFormat"><span data-ttu-id="22108-106">BLOB-Benennungskonvention für die Archivierung, z. B. {Namespace} / {EventHub} / {PartitionId} / {Year} / {Month} / {Day} / {Stunde} / {Minute} / {Sekunde}.</span><span class="sxs-lookup"><span data-stu-id="22108-106">Blob naming convention for archive, e.g. {Namespace}/{EventHub}/{PartitionId}/{Year}/{Month}/{Day}/{Hour}/{Minute}/{Second}.</span></span>
            <span data-ttu-id="22108-107">Hier alle Parameter ("Namespace", "EventHub"..</span><span class="sxs-lookup"><span data-stu-id="22108-107">Here all the parameters (Namespace,EventHub ..</span></span> <span data-ttu-id="22108-108">usw.) müssen unabhängig von der Reihenfolge angegeben werden</span><span class="sxs-lookup"><span data-stu-id="22108-108">etc) are mandatory irrespective of order</span></span></param>
        <summary>
            <span data-ttu-id="22108-109">Initialisiert eine neue Instanz der Ziel-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22108-109">Initializes a new instance of the Destination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ArchiveNameFormat">
      <MemberSignature Language="C#" Value="public string ArchiveNameFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ArchiveNameFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.ArchiveNameFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property ArchiveNameFormat As String" />
      <MemberSignature Language="F#" Value="member this.ArchiveNameFormat : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.ArchiveNameFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22108-110">Ruft ab oder legt ihn fest-BLOB-Benennungskonvention für die Archivierung, z. B. {Namespace} / {EventHub} / {PartitionId} / {Year} / {Month} / {Day} / {Stunde} / {Minute} / {Sekunde}.</span><span class="sxs-lookup"><span data-stu-id="22108-110">Gets or sets blob naming convention for archive, e.g. {Namespace}/{EventHub}/{PartitionId}/{Year}/{Month}/{Day}/{Hour}/{Minute}/{Second}.</span></span>
            <span data-ttu-id="22108-111">Hier alle Parameter ("Namespace", "EventHub"..</span><span class="sxs-lookup"><span data-stu-id="22108-111">Here all the parameters (Namespace,EventHub ..</span></span> <span data-ttu-id="22108-112">usw.) müssen unabhängig von der Reihenfolge angegeben werden</span><span class="sxs-lookup"><span data-stu-id="22108-112">etc) are mandatory irrespective of order</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobContainer">
      <MemberSignature Language="C#" Value="public string BlobContainer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.BlobContainer" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobContainer As String" />
      <MemberSignature Language="F#" Value="member this.BlobContainer : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.BlobContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22108-113">Ruft ab oder legt ihn fest-Blob-Container namens</span><span class="sxs-lookup"><span data-stu-id="22108-113">Gets or sets blob container Name</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22108-114">Ruft ab oder legt ihn fest für Capture-Ziel</span><span class="sxs-lookup"><span data-stu-id="22108-114">Gets or sets name for capture destination</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountResourceId">
      <MemberSignature Language="C#" Value="public string StorageAccountResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Destination.StorageAccountResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountResourceId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountResourceId : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Destination.StorageAccountResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22108-115">Ruft ab oder legt ihn fest Ressourcen-Id des Speicherkontos verwendet werden, um die Blobs zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="22108-115">Gets or sets resource id of the storage account to be used to create the blobs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>