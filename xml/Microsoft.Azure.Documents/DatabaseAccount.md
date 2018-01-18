<Type Name="DatabaseAccount" FullName="Microsoft.Azure.Documents.DatabaseAccount">
  <TypeSignature Language="C#" Value="public class DatabaseAccount : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseAccount extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.DatabaseAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseAccount = class&#xA;    inherit Resource" />
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
  <Interfaces />
  <Docs>
    <summary> 
            <span data-ttu-id="29933-101">Stellt ein Datenbankkonto dar.</span><span class="sxs-lookup"><span data-stu-id="29933-101">Represents a DatabaseAccount.</span></span> <span data-ttu-id="29933-102">Ein Datenbankkonto ist der Container für Datenbanken im Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="29933-102">A DatabaseAccount is the container for databases in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ConsistencyPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ConsistencyPolicy ConsistencyPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.ConsistencyPolicy ConsistencyPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyPolicy As ConsistencyPolicy" />
      <MemberSignature Language="F#" Value="member this.ConsistencyPolicy : Microsoft.Azure.Documents.ConsistencyPolicy" Usage="Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" />
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
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ConsistencyPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-103">Ruft die <see cref="P:Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" /> Einstellungen aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="29933-103">Gets the <see cref="P:Microsoft.Azure.Documents.DatabaseAccount.ConsistencyPolicy" /> settings from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="29933-104">Die ConsistencyPolicy-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="29933-104">The ConsistencyPolicy settings.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabasesLink">
      <MemberSignature Language="C#" Value="public string DatabasesLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabasesLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.DatabasesLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabasesLink As String" />
      <MemberSignature Language="F#" Value="member this.DatabasesLink : string" Usage="Microsoft.Azure.Documents.DatabaseAccount.DatabasesLink" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_dbs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-105">Ruft die Self-link für Datenbanken in der Datenbankkonto aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="29933-105">Gets the self-link for Databases in the databaseAccount from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="29933-106">Der Self-link für Datenbanken in der Datenbankkonto.</span><span class="sxs-lookup"><span data-stu-id="29933-106">The self-link for Databases in the databaseAccount.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxMediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long MaxMediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxMediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MaxMediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxMediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MaxMediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.DatabaseAccount.MaxMediaStorageUsageInMB" />
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
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-107">Ruft das Speicherkontingent für die Speicherung von Medien in der Datenbankkonto aus dem Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="29933-107">Gets the storage quota for media storage in the databaseAccount from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="29933-108">Das Speicherkontingent in gemessene MB.</span><span class="sxs-lookup"><span data-stu-id="29933-108">The storage quota in measured MBs.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="29933-109">Dieser Wert wird vom Gateway abgerufen.</span><span class="sxs-lookup"><span data-stu-id="29933-109">This value is retrieved from the gateway.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaLink">
      <MemberSignature Language="C#" Value="public string MediaLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MediaLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MediaLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MediaLink As String" />
      <MemberSignature Language="F#" Value="member this.MediaLink : string" Usage="Microsoft.Azure.Documents.DatabaseAccount.MediaLink" />
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
            <span data-ttu-id="29933-110">Ruft die Self-link für Medium in das Datenbankkonto aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="29933-110">Gets the self-link for Media in the databaseAccount from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="29933-111">Der Self-link für das Medium in das Datenbankkonto.</span><span class="sxs-lookup"><span data-stu-id="29933-111">The self-link for Media in the databaseAccount.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MediaStorageUsageInMB">
      <MemberSignature Language="C#" Value="public long MediaStorageUsageInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MediaStorageUsageInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.MediaStorageUsageInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MediaStorageUsageInMB As Long" />
      <MemberSignature Language="F#" Value="member this.MediaStorageUsageInMB : int64" Usage="Microsoft.Azure.Documents.DatabaseAccount.MediaStorageUsageInMB" />
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
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-112">Ruft die aktuelle Verwendung der Anlage Inhalt (Medium) in MB ab, aus dem Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="29933-112">Gets the current attachment content (media) usage in MBs from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="29933-113">Die Attachment-Inhalt (Medium)-Verwendung in MB.</span><span class="sxs-lookup"><span data-stu-id="29933-113">The attachment content (media) usage in MBs.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="29933-114">Der Wert wird vom Gateway abgerufen.</span><span class="sxs-lookup"><span data-stu-id="29933-114">The value is retrieved from the gateway.</span></span> <span data-ttu-id="29933-115">Der Wert wird zurückgegeben, zwischengespeicherte Informationen, die in regelmäßigen Abständen aktualisiert und ist nicht unbedingt Echtzeit.</span><span class="sxs-lookup"><span data-stu-id="29933-115">The value is returned from cached information updated periodically and is not guaranteed to be real time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadableLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt; ReadableLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.DatabaseAccountLocation&gt; ReadableLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.ReadableLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadableLocations As IEnumerable(Of DatabaseAccountLocation)" />
      <MemberSignature Language="F#" Value="member this.ReadableLocations : seq&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;" Usage="Microsoft.Azure.Documents.DatabaseAccount.ReadableLocations" />
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
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-116">Ruft der Liste der Speicherorte Reprsenting lesbaren Regionen dieses Datenbankkonto aus dem Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="29933-116">Gets the list of locations reprsenting the readable regions of this database account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WritableLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt; WritableLocations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Documents.DatabaseAccountLocation&gt; WritableLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.DatabaseAccount.WritableLocations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WritableLocations As IEnumerable(Of DatabaseAccountLocation)" />
      <MemberSignature Language="F#" Value="member this.WritableLocations : seq&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;" Usage="Microsoft.Azure.Documents.DatabaseAccount.WritableLocations" />
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
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Documents.DatabaseAccountLocation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="29933-117">Ruft der Liste der Speicherorte Reprsenting beschreibbaren Regionen dieses Datenbankkonto aus dem Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="29933-117">Gets the list of locations reprsenting the writable regions of this database account from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>