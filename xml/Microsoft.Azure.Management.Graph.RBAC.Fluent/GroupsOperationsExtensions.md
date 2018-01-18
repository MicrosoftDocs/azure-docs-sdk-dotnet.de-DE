<Type Name="GroupsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GroupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GroupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GroupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GroupsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ff6f5-101">Erweiterungsmethoden für GroupsOperations.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-101">Extension methods for GroupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddMemberAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task AddMemberAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task AddMemberAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.AddMemberAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddMemberAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.AddMemberAsync (operations, groupObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;AddMemberAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupAddMemberParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="groupObjectId">
            <span data-ttu-id="ff6f5-103">Die Objekt-ID der Gruppe, der das Element hinzugefügt werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-103">The object ID of the group to which to add the member.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ff6f5-104">Die URL des Member-Objekt, z. B. https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-104">The URL of the member object, such as https://graph.windows.net/0b1f9851-1bf0-433f-aec3-cb9272f093dc/directoryObjects/f260bbc4-c254-447b-94cf-293b5ec434dd.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-106">Hinzufügen eines Mitglieds zu einer Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-106">Add a member to a group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;CreateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-107">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ff6f5-108">Die Parameter für die Gruppe zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-108">The parameters for the group to create.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-110">Erstellen Sie eine Gruppe im Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-110">Create a group in the directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.DeleteAsync (operations, groupObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-111">The operations group for this extension method.</span></span>
            </param>
        <param name="groupObjectId">
            <span data-ttu-id="ff6f5-112">Die Objekt-ID der Gruppe zu löschen.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-112">The object ID of the group to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-114">Löschen Sie eine Gruppe aus dem Verzeichnis ein.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-114">Delete a group from the directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-115">The operations group for this extension method.</span></span>
            </param>
        <param name="objectId">
            <span data-ttu-id="ff6f5-116">Die Objekt-ID des Benutzers für die Gruppeninformationen abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-116">The object ID of the user for which to get group information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-118">Ruft Informationen aus dem Verzeichnis zu gruppieren.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-118">Gets group information from the directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGroupMembersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGroupMembersAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersAsync (operations, objectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetGroupMembersAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-119">The operations group for this extension method.</span></span>
            </param>
        <param name="objectId">
            <span data-ttu-id="ff6f5-120">Die Objekt-ID der Gruppe, deren Mitglieder abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-120">The object ID of the group whose members should be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-122">Ruft die Mitglieder einer Gruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-122">Gets the members of a group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGroupMembersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt; GetGroupMembersNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGroupMembersNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetGroupMembersNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetGroupMembersNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.AADObjectInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ff6f5-124">Nächsten Link für den List-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-124">Next link for the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-126">Ruft die Mitglieder einer Gruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-126">Gets the members of a group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMemberGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetMemberGroupsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetMemberGroupsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetMemberGroupsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMemberGroupsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.GetMemberGroupsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;GetMemberGroupsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.GroupGetMemberGroupsParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-127">The operations group for this extension method.</span></span>
            </param>
        <param name="objectId">
            <span data-ttu-id="ff6f5-128">Die Objekt-ID der Gruppe für die Gruppenmitgliedschaft abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-128">The object ID of the group for which to get group membership.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ff6f5-129">Gruppieren Sie Filterparameter ein.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-129">Group filtering parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-131">Ruft eine Auflistung der Objekt-IDs der Gruppen, die Mitglied die angegebene Gruppe ist.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-131">Gets a collection of object IDs of groups of which the specified group is a member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMemberOfAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt; IsMemberOfAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt; IsMemberOfAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.IsMemberOfAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IsMemberOfAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.IsMemberOfAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;IsMemberOfAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.CheckGroupMembershipParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-132">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ff6f5-133">Die Überprüfung der Gruppenmitgliedschaft-Parameter.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-133">The check group membership parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-135">Überprüft, ob der angegebene Benutzer, Gruppe, Kontakt oder Dienstprinzipal direkt oder transitiv Mitglied der angegebenen Gruppe ist.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-135">Checks whether the specified user, group, contact, or service principal is a direct or transitive member of the specified group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-136">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="ff6f5-137">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-137">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-139">Ruft die Liste der Gruppen für den aktuellen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-139">Gets list of groups for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ADGroupInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-140">The operations group for this extension method.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ff6f5-141">Nächsten Link für den List-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-141">Next link for the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-143">Ruft eine Liste von Gruppen für den aktuellen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-143">Gets a list of groups for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveMemberAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RemoveMemberAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, string memberObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RemoveMemberAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations operations, string groupObjectId, string memberObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.RemoveMemberAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RemoveMemberAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions.RemoveMemberAsync (operations, groupObjectId, memberObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.GroupsOperationsExtensions/&lt;RemoveMemberAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IGroupsOperations" RefType="this" />
        <Parameter Name="groupObjectId" Type="System.String" />
        <Parameter Name="memberObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ff6f5-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-144">The operations group for this extension method.</span></span>
            </param>
        <param name="groupObjectId">
            <span data-ttu-id="ff6f5-145">Die Objekt-ID der Gruppe aus dem das Element entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-145">The object ID of the group from which to remove the member.</span></span>
            </param>
        <param name="memberObjectId">
            <span data-ttu-id="ff6f5-146">Member-Objekt-id</span><span class="sxs-lookup"><span data-stu-id="ff6f5-146">Member object id</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ff6f5-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ff6f5-148">Entfernen eines Mitglieds aus einer Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="ff6f5-148">Remove a member from a group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>