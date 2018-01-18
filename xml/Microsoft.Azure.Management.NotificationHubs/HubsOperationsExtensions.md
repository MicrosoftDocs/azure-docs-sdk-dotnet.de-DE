<Type Name="HubsOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class HubsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HubsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HubsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type HubsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0ef6-101">Erweiterungsmethoden für HubsOperations.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-101">Extension methods for HubsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.IHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.IHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.IHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As IHubsOperations, resourceGroupName As String, namespaceName As String, parameters As CheckNameAvailabilityRequestParameters) As CheckNameAvailabilityResponse" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.IHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse" Usage="Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions.CheckAvailability (operations, resourceGroupName, namespaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.IHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0ef6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0ef6-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-103">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0ef6-104">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-104">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0ef6-105">Der NotificationHub-Name.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-105">The notificationHub name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0ef6-106">Überprüft die Verfügbarkeit von der angegebenen NotificationHub in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-106">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.IHubsOperations operations, string resourceGroupName, string namespaceName, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.IHubsOperations operations, string resourceGroupName, string namespaceName, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.IHubsOperations,System.String,System.String,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.IHubsOperations * string * string * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions.CheckAvailabilityAsync (operations, resourceGroupName, namespaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.HubsOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.IHubsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c0ef6-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c0ef6-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-108">The name of the resource group.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="c0ef6-109">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-109">The namespace name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c0ef6-110">Der NotificationHub-Name.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-110">The notificationHub name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0ef6-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0ef6-112">Überprüft die Verfügbarkeit von der angegebenen NotificationHub in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="c0ef6-112">Checks the availability of the given notificationHub in a namespace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>