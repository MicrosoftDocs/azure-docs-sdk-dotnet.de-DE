<Type Name="ConnectionMode" FullName="Microsoft.Azure.Documents.Client.ConnectionMode">
  <TypeSignature Language="C#" Value="public enum ConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.ConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectionMode" />
  <TypeSignature Language="F#" Value="type ConnectionMode = " />
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
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="715f7-101">Stellt den Verbindungsmodus auf die vom Client verwendet werden, wenn eine Verbindung mit der Azure-Cosmos-DB-Dienst herstellen.</span><span class="sxs-lookup"><span data-stu-id="715f7-101">Represents the connection mode to be used by the client when connecting to the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="715f7-102">Gateway Konnektivität Modi "und" Direct werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="715f7-102">Direct and Gateway connectivity modes are supported.</span></span> <span data-ttu-id="715f7-103">Gateway ist die Standardeinstellung.</span><span class="sxs-lookup"><span data-stu-id="715f7-103">Gateway is the default.</span></span> 
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Client.ConnectionPolicy" />
    <altmember cref="T:Microsoft.Azure.Documents.Client.Protocol" />
    <example>
      <code language="c#"><![CDATA[
            DocumentClient client = new DocumentClient(endpointUri, masterKey, new ConnectionPolicy { ConnectionMode = ConnectionMode.Direct });
            ]]></code>
    </example>
  </Docs>
  <Members>
    <Member MemberName="Direct">
      <MemberSignature Language="C#" Value="Direct" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Direct = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
      <MemberSignature Language="VB.NET" Value="Direct" />
      <MemberSignature Language="F#" Value="Direct = 1" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Direct" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="715f7-104">Verwendet direkte Verbindung mit der Datenknoten im Azure-Cosmos-DB-Dienst herstellen.</span><span class="sxs-lookup"><span data-stu-id="715f7-104">Uses direct connectivity to connect to the data nodes in the Azure Cosmos DB service.</span></span> <span data-ttu-id="715f7-105">Gateway nur zu initialisieren und Cache logischen Adressen verwendet werden, und aktualisieren Sie auf updates</span><span class="sxs-lookup"><span data-stu-id="715f7-105">Use gateway only to initialize and cache logical addresses and refresh on updates</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="715f7-106">Verwenden Sie direkten Konnektivität für optimale Leistung zu erzielen.</span><span class="sxs-lookup"><span data-stu-id="715f7-106">Use Direct connectivity for best performance.</span></span> <span data-ttu-id="715f7-107">Auf den Datenknoten auf Azure Cosmos-DB-Clustern für einen Bereich von Portnummern Verbindungen hergestellt werden, entweder über HTTPS oder TCP/SSL.</span><span class="sxs-lookup"><span data-stu-id="715f7-107">Connections are made to the data nodes on Azure Cosmos DB's clusters on a range of port numbers either using HTTPS or TCP/SSL.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Gateway">
      <MemberSignature Language="C#" Value="Gateway" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.ConnectionMode Gateway = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
      <MemberSignature Language="VB.NET" Value="Gateway" />
      <MemberSignature Language="F#" Value="Gateway = 0" Usage="Microsoft.Azure.Documents.Client.ConnectionMode.Gateway" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Client.ConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="715f7-108">Verwenden Sie das Azure-Cosmos-DB-Gateway, um alle Anforderungen an den Azure-Cosmos-DB-Dienst weiterzuleiten.</span><span class="sxs-lookup"><span data-stu-id="715f7-108">Use the Azure Cosmos DB gateway to route all requests to the Azure Cosmos DB service.</span></span> <span data-ttu-id="715f7-109">Die Gateway-Proxys-Anforderungen in der richtigen Datenpartition.</span><span class="sxs-lookup"><span data-stu-id="715f7-109">The gateway proxies requests to the right data partition.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="715f7-110">Verwenden Sie gatewaykonnektivität, wenn innerhalb der Firewall Settings keine direkte Verbindung zulassen.</span><span class="sxs-lookup"><span data-stu-id="715f7-110">Use Gateway connectivity when within firewall settings do not allow Direct connectivity.</span></span> <span data-ttu-id="715f7-111">Alle Verbindungen werden auf dem Datenbankkonto Endpunkt durch die HTTPS-Standardport (Port 443) hergestellt.</span><span class="sxs-lookup"><span data-stu-id="715f7-111">All connections are made to the database account's endpoint through the standard HTTPS port (443).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>