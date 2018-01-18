<Type Name="ProtectionContainerOperationResultsOperationsExtensions" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProtectionContainerOperationResultsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProtectionContainerOperationResultsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProtectionContainerOperationResultsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProtectionContainerOperationResultsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="129a0-101">Erweiterungsmethoden für ProtectionContainerOperationResultsOperations.</span><span class="sxs-lookup"><span data-stu-id="129a0-101">Extension methods for ProtectionContainerOperationResultsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource Get(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions.Get(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProtectionContainerOperationResultsOperations, vaultName As String, resourceGroupName As String, fabricName As String, containerName As String, operationId As String) As ProtectionContainerResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions.Get (operations, vaultName, resourceGroupName, fabricName, containerName, operationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="129a0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="129a0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="129a0-103">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="129a0-103">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="129a0-104">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="129a0-104">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="129a0-105">Fabric-Namen, die dem Container zugewiesen sind.</span><span class="sxs-lookup"><span data-stu-id="129a0-105">Fabric name associated with the container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="129a0-106">Der Containername, deren Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="129a0-106">Container name whose information should be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="129a0-107">Vorgangs-ID der den Vorgang darstellt, dessen Ergebnis abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="129a0-107">Operation ID which represents the operation whose result needs to be fetched.</span></span>
            </param>
        <summary>
            <span data-ttu-id="129a0-108">Ruft das Ergebnis der Vorgänge auf den Container ab.</span><span class="sxs-lookup"><span data-stu-id="129a0-108">Fetches the result of any operation on the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync (this Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string operationId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt; GetAsync(class Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations operations, string vaultName, string resourceGroupName, string fabricName, string containerName, string operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions.GetAsync(Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions.GetAsync (operations, vaultName, resourceGroupName, fabricName, containerName, operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.RecoveryServices.Backup.ProtectionContainerOperationResultsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainerResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.RecoveryServices.Backup.IProtectionContainerOperationResultsOperations" RefType="this" />
        <Parameter Name="vaultName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="fabricName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="129a0-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="129a0-109">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultName">
            <span data-ttu-id="129a0-110">Der Name des Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="129a0-110">The name of the recovery services vault.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="129a0-111">Der Name der Ressourcengruppe, in dem die Recovery-Tresor Services, ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="129a0-111">The name of the resource group where the recovery services vault is present.</span></span>
            </param>
        <param name="fabricName">
            <span data-ttu-id="129a0-112">Fabric-Namen, die dem Container zugewiesen sind.</span><span class="sxs-lookup"><span data-stu-id="129a0-112">Fabric name associated with the container.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="129a0-113">Der Containername, deren Informationen abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="129a0-113">Container name whose information should be fetched.</span></span>
            </param>
        <param name="operationId">
            <span data-ttu-id="129a0-114">Vorgangs-ID der den Vorgang darstellt, dessen Ergebnis abgerufen werden muss.</span><span class="sxs-lookup"><span data-stu-id="129a0-114">Operation ID which represents the operation whose result needs to be fetched.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="129a0-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="129a0-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="129a0-116">Ruft das Ergebnis der Vorgänge auf den Container ab.</span><span class="sxs-lookup"><span data-stu-id="129a0-116">Fetches the result of any operation on the container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>