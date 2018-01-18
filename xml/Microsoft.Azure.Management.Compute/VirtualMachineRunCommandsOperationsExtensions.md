<Type Name="VirtualMachineRunCommandsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineRunCommandsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineRunCommandsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineRunCommandsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineRunCommandsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bf64b-101">Erweiterungsmethoden für VirtualMachineRunCommandsOperations.</span><span class="sxs-lookup"><span data-stu-id="bf64b-101">Extension methods for VirtualMachineRunCommandsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.RunCommandDocument Get (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, string commandId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.RunCommandDocument Get(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, string commandId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineRunCommandsOperations, location As String, commandId As String) As RunCommandDocument" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandDocument" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.Get (operations, location, commandId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RunCommandDocument</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="commandId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="bf64b-103">Der Speicherort der führen Sie Befehle abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="bf64b-103">The location upon which run commands is queried.</span></span>
            </param>
        <param name="commandId">
            <span data-ttu-id="bf64b-104">Die Befehls-Id.</span><span class="sxs-lookup"><span data-stu-id="bf64b-104">The command id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-105">Ruft bestimmte ausgeführten Befehls für ein Abonnement an einem Ort.</span><span class="sxs-lookup"><span data-stu-id="bf64b-105">Gets specific run command for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocument&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, string commandId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandDocument&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, string commandId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocument&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.GetAsync (operations, location, commandId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocument&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="commandId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-106">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="bf64b-107">Der Speicherort der führen Sie Befehle abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="bf64b-107">The location upon which run commands is queried.</span></span>
            </param>
        <param name="commandId">
            <span data-ttu-id="bf64b-108">Die Befehls-Id.</span><span class="sxs-lookup"><span data-stu-id="bf64b-108">The command id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf64b-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bf64b-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-110">Ruft bestimmte ausgeführten Befehls für ein Abonnement an einem Ort.</span><span class="sxs-lookup"><span data-stu-id="bf64b-110">Gets specific run command for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachineRunCommandsOperations, location As String) As IPage(Of RunCommandDocumentBase)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.List (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-111">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="bf64b-112">Der Speicherort der führen Sie Befehle abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="bf64b-112">The location upon which run commands is queried.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-113">Listet alle verfügbaren Ausführen von Befehlen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="bf64b-113">Lists all available run commands for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-114">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="bf64b-115">Der Speicherort der führen Sie Befehle abgefragt wird.</span><span class="sxs-lookup"><span data-stu-id="bf64b-115">The location upon which run commands is queried.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf64b-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bf64b-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-117">Listet alle verfügbaren Ausführen von Befehlen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="bf64b-117">Lists all available run commands for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachineRunCommandsOperations, nextPageLink As String) As IPage(Of RunCommandDocumentBase)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-118">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bf64b-119">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bf64b-119">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-120">Listet alle verfügbaren Ausführen von Befehlen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="bf64b-120">Lists all available run commands for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineRunCommandsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.RunCommandDocumentBase&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineRunCommandsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bf64b-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bf64b-121">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bf64b-122">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bf64b-122">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bf64b-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bf64b-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bf64b-124">Listet alle verfügbaren Ausführen von Befehlen für ein Abonnement in einen Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="bf64b-124">Lists all available run commands for a subscription in a location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>