<Type Name="NameOperationsExtensions" FullName="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NameOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NameOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NameOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NameOperationsExtensions = class" />
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
            <span data-ttu-id="c5b1a-101">Erweiterungsmethoden für NameOperations.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-101">Extension methods for NameOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability (this Microsoft.Azure.Management.NotificationHubs.INameOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse CheckAvailability(class Microsoft.Azure.Management.NotificationHubs.INameOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailability(Microsoft.Azure.Management.NotificationHubs.INameOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckAvailability (operations As INameOperations, parameters As CheckNameAvailabilityRequestParameters) As CheckNameAvailabilityResponse" />
      <MemberSignature Language="F#" Value="static member CheckAvailability : Microsoft.Azure.Management.NotificationHubs.INameOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters -&gt; Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse" Usage="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailability (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INameOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c5b1a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c5b1a-103">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-103">The namespace name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5b1a-104">Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-104">Checks the availability of the given service namespace across all Azure subscriptions.</span></span> <span data-ttu-id="c5b1a-105">Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-105">This is useful because the domain name is created based on the service namespace name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync (this Microsoft.Azure.Management.NotificationHubs.INameOperations operations, Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt; CheckAvailabilityAsync(class Microsoft.Azure.Management.NotificationHubs.INameOperations operations, class Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailabilityAsync(Microsoft.Azure.Management.NotificationHubs.INameOperations,Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckAvailabilityAsync : Microsoft.Azure.Management.NotificationHubs.INameOperations * Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;" Usage="Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions.CheckAvailabilityAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.NotificationHubs.NameOperationsExtensions/&lt;CheckAvailabilityAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.NotificationHubs.INameOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.NotificationHubs.Models.CheckNameAvailabilityRequestParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c5b1a-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-106">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c5b1a-107">Der Namespacename.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-107">The namespace name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c5b1a-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c5b1a-109">Überprüft die Verfügbarkeit des angegebenen Dienstnamespace über alle Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-109">Checks the availability of the given service namespace across all Azure subscriptions.</span></span> <span data-ttu-id="c5b1a-110">Dies ist hilfreich, da der Domänenname basierend auf den Dienstnamespace erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="c5b1a-110">This is useful because the domain name is created based on the service namespace name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>