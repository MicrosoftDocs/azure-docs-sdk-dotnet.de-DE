<Type Name="ServicePackageActivationMode" FullName="System.Fabric.Description.ServicePackageActivationMode">
  <TypeSignature Language="C#" Value="public enum ServicePackageActivationMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ServicePackageActivationMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ServicePackageActivationMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ServicePackageActivationMode" />
  <TypeSignature Language="F#" Value="type ServicePackageActivationMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>
            Beschreibt Dienstmodus Paket Aktivierung für einen Service Fabric-Dienst an. <span data-ttu-id="62bff-102">Dadurch wird angegeben, die zum Zeitpunkt der Erstellung des Diensts (mit <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) oder Dienstgruppe (mit <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) über <see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="62bff-102">This is specified at the time of creating the Service (using <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />) or ServiceGroup (using <see cref="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />) via <see cref="P:System.Fabric.Description.ServiceDescription.ServicePackageActivationMode" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="62bff-103">Wenn beim Erstellen des Diensts oder einer Dienstgruppe wurde kein Wert angegeben, wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> Modus.</span><span class="sxs-lookup"><span data-stu-id="62bff-103">If no value is specified while creating the Service or ServiceGroup, then it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> mode.</span></span>
            </para>
    </summary>
    <remarks>
      <para>
            <span data-ttu-id="62bff-104">Betrachten Sie ein Beispiel, in dem Sie haben einen Anwendungstyp für "AppTypeA" das ServicePackage "ServicePackageA" registriert "ServiceTypeA" enthält und Sie viele Dienste von "ServiceTypeA" erstellen.</span><span class="sxs-lookup"><span data-stu-id="62bff-104">Consider an example where you have an ApplicationType 'AppTypeA' which contains ServicePackage 'ServicePackageA' which registers 'ServiceTypeA' and you create many Service(s) of 'ServiceTypeA'.</span></span> <span data-ttu-id="62bff-105">Sagen "Fabric: / App1_of_AppTypeA/Serv_1" auf "Fabric: / App1_of_AppTypeA/Serv_N" mit ServicePackageActivation Modus <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> und "Fabric: / App1_of_AppTypeA/Serv_11", "Fabric: / App1_of_AppTypeA/Serv_NN" mit ServicePackageActivation-Modus <see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.</span><span class="sxs-lookup"><span data-stu-id="62bff-105">Say 'fabric:/App1_of_AppTypeA/Serv_1' to 'fabric:/App1_of_AppTypeA/Serv_N' with ServicePackageActivation mode <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> and 'fabric:/App1_of_AppTypeA/Serv_11' to 'fabric:/App1_of_AppTypeA/Serv_NN' with ServicePackageActivation mode <see cref="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="62bff-106">Auf einem bestimmten Knoten, Replikat (oder Instanz) des Diensts "Fabric: / App1_of_AppTypeA/Serv_1", "Fabric: / App1_of_AppTypeA/Serv_N" wird platziert werden die gleichen Aktivierung "ServicePackageA", deren <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> wird immer eine leere Zeichenfolge sein.</span><span class="sxs-lookup"><span data-stu-id="62bff-106">On a given node, replica (or instance) of service 'fabric:/App1_of_AppTypeA/Serv_1' to 'fabric:/App1_of_AppTypeA/Serv_N' will be placed inside the same activation of 'ServicePackageA' whose <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> will always be an empty string.</span></span> <span data-ttu-id="62bff-107">Allerdings Replikat (oder Instanz) der einzelnen "Fabric: / App1_of_AppTypeA/Serv_11", "Fabric: / App1_of_AppTypeA/Serv_NN" eingefügt wird in einen eigenen dedizierten Aktivierung von "ServicePackageA", und jede dieser Aktivierung wird eine eindeutige nicht leere Zeichenfolge als haben<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.</span><span class="sxs-lookup"><span data-stu-id="62bff-107">However, replica (or instance) of each of  'fabric:/App1_of_AppTypeA/Serv_11' to 'fabric:/App1_of_AppTypeA/Serv_NN' will be placed in its own dedicated activation of 'ServicePackageA' and each of these activation will have a unique non-empty string as <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />.</span></span>
            </para>
      <para>
            <span data-ttu-id="62bff-108">Nachdem Sie den Dienst erstellt haben, erhalten Sie <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> der aktivierten ServicePackage(s) auf einen Knoten durch Abfragen <see cref="T:System.Fabric.Query.DeployedServicePackageList" /> auf diesem Knoten mithilfe <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />.</span><span class="sxs-lookup"><span data-stu-id="62bff-108">After you have created your service, you can obtain <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of activated ServicePackage(s) on a node by querying <see cref="T:System.Fabric.Query.DeployedServicePackageList" /> on that node using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ExclusiveProcess">
      <MemberSignature Language="C#" Value="ExclusiveProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode ExclusiveProcess = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberSignature Language="VB.NET" Value="ExclusiveProcess" />
      <MemberSignature Language="F#" Value="ExclusiveProcess = 1" Usage="System.Fabric.Description.ServicePackageActivationMode.ExclusiveProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="62bff-109">Mit dieser Aktivierung müssen Modus, jedes Replikat oder eine Instanz des Diensts auf einem bestimmten Knoten eine eigenen dedizierte Aktivierung des Dienstpakets auf einem Knoten.</span><span class="sxs-lookup"><span data-stu-id="62bff-109">With this activation mode, each replica or instance of service, on a given node, will have its own dedicated activation of service package on a node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="SharedProcess">
      <MemberSignature Language="C#" Value="SharedProcess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Description.ServicePackageActivationMode SharedProcess = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberSignature Language="VB.NET" Value="SharedProcess" />
      <MemberSignature Language="F#" Value="SharedProcess = 0" Usage="System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ServicePackageActivationMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="62bff-110">Dies ist der Standardmodus für die Aktivierung.</span><span class="sxs-lookup"><span data-stu-id="62bff-110">This is the default activation mode.</span></span> <span data-ttu-id="62bff-111">Für diese Aktivierung werden Modus, Replikate oder Instanzen aus anderen Partitionen der Dienst auf einem bestimmten Knoten denselben Aktivierung des Dienstpakets auf einem Knoten freigeben.</span><span class="sxs-lookup"><span data-stu-id="62bff-111">With this activation mode, replica(s) or instance(s) from different partition(s) of service, on a given node, will share same activation of service package on a node.</span></span>
            </para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>