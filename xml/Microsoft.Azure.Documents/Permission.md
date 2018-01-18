<Type Name="Permission" FullName="Microsoft.Azure.Documents.Permission">
  <TypeSignature Language="C#" Value="public class Permission : Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Permission extends Microsoft.Azure.Documents.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Permission" />
  <TypeSignature Language="VB.NET" Value="Public Class Permission&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Permission = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="9f6cb-101">Stellt eine benutzerspezifische Berechtigung Zugriff auf eine bestimmte Ressource in der Azure-Cosmos-DB-Dienst, z. B. Dokument oder einer Auflistung dar.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-101">Represents a per-User permission to access a specific resource in the Azure Cosmos DB service, for example Document or Collection.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Permission ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Permission.#ctor" />
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
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PermissionMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PermissionMode PermissionMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Documents.PermissionMode PermissionMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.PermissionMode" />
      <MemberSignature Language="VB.NET" Value="Public Property PermissionMode As PermissionMode" />
      <MemberSignature Language="F#" Value="member this.PermissionMode : Microsoft.Azure.Documents.PermissionMode with get, set" Usage="Microsoft.Azure.Documents.Permission.PermissionMode" />
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
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="permissionMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PermissionMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6cb-102">Ruft ab oder legt den Berechtigungsmodus in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-102">Gets or sets the permission mode in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9f6cb-103">Die <see cref="P:Microsoft.Azure.Documents.Permission.PermissionMode" /> Modus: Lese- oder alle.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-103">The <see cref="P:Microsoft.Azure.Documents.Permission.PermissionMode" /> mode: Read or All.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceLink">
      <MemberSignature Language="C#" Value="public string ResourceLink { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.ResourceLink" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceLink As String" />
      <MemberSignature Language="F#" Value="member this.ResourceLink : string with get, set" Usage="Microsoft.Azure.Documents.Permission.ResourceLink" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary> 
            <span data-ttu-id="9f6cb-104">Ruft ab, oder legt ihn fest der Self-link der Ressource, die für das die Berechtigung gilt, in der Azure-Cosmos-DB-Dienst.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-104">Gets or sets the self-link of resource to which the permission applies in the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9f6cb-105">Der Self-link der Ressource für die die Berechtigung gilt.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-105">The self-link of the resource to which the permission applies.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourcePartitionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.PartitionKey ResourcePartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.PartitionKey ResourcePartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourcePartitionKey As PartitionKey" />
      <MemberSignature Language="F#" Value="member this.ResourcePartitionKey : Microsoft.Azure.Documents.PartitionKey with get, set" Usage="Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourcePartitionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.PartitionKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6cb-106">Ruft ab, oder legt Sie optionale partitionsschlüsselwert für die Berechtigung in den Azure-Cosmos-DB-Dienst fest.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-106">Gets or sets optional partition key value for the permission in the Azure Cosmos DB service.</span></span>
            <span data-ttu-id="9f6cb-107">Eine Berechtigung gilt für Ressourcen, wenn zwei Bedingungen erfüllt sind:</span><span class="sxs-lookup"><span data-stu-id="9f6cb-107">A permission applies to resources when two conditions are met:</span></span>
                  1. <span data-ttu-id="9f6cb-108"><see cref="P:Microsoft.Azure.Documents.Permission.ResourceLink" />Präfix der Verknüpfung der Ressource ist.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-108"><see cref="P:Microsoft.Azure.Documents.Permission.ResourceLink" /> is prefix of resource's link.</span></span>
                        <span data-ttu-id="9f6cb-109">Gilt z. B. "/ Dbs/Mydatabase/colls/Mycollection", "/ Dbs/Mydatabase/colls/Mycollection" und "/ Dbs/Mydatabase/colls/Mycollection/Dokumente/Mydocument"</span><span class="sxs-lookup"><span data-stu-id="9f6cb-109">For example "/dbs/mydatabase/colls/mycollection" applies to "/dbs/mydatabase/colls/mycollection" and "/dbs/mydatabase/colls/mycollection/docs/mydocument"</span></span>
                  2. <span data-ttu-id="9f6cb-110"><see cref="P:Microsoft.Azure.Documents.Permission.ResourcePartitionKey" />ist übergeordnet Partitionsschlüssel der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-110"><see cref="P:Microsoft.Azure.Documents.Permission.ResourcePartitionKey" /> is superset of resource's partition key.</span></span>
                        <span data-ttu-id="9f6cb-111">Beispielsweise ist nicht vorhanden oder leer Partitionsschlüssel Obermenge von alle Partitionsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-111">For example absent/empty partition key is superset of all partition keys.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Token">
      <MemberSignature Language="C#" Value="public string Token { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Token" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Permission.Token" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Token As String" />
      <MemberSignature Language="F#" Value="member this.Token : string" Usage="Microsoft.Azure.Documents.Permission.Token" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="_token")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6cb-112">Ruft das Zugriffstoken definierten Berechtigung aus dem Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-112">Gets the access token granting the defined permission from the Azure Cosmos DB service.</span></span>
            </summary>
        <value>
            <span data-ttu-id="9f6cb-113">Das Zugriffstoken, die die definierte Berechtigung erteilen.</span><span class="sxs-lookup"><span data-stu-id="9f6cb-113">The access token granting the defined permission.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>