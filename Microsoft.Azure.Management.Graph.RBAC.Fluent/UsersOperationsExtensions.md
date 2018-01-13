<Type Name="UsersOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsersOperationsExtensions = class" />
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
            <span data-ttu-id="5befb-101">Erweiterungsmethoden für UsersOperations.</span><span class="sxs-lookup"><span data-stu-id="5befb-101">Extension methods for UsersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5befb-103">Parameter zum Erstellen eines Benutzers.</span><span class="sxs-lookup"><span data-stu-id="5befb-103">Parameters to create a user.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-105">Erstellen eines neuen Benutzers an.</span><span class="sxs-lookup"><span data-stu-id="5befb-105">Create a new user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.DeleteAsync (operations, upnOrObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;DeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-106">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="5befb-107">Die Objekt-ID oder der Prinzipalname des Benutzers gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5befb-107">The object ID or principal name of the user to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-109">Löschen eines Benutzers an.</span><span class="sxs-lookup"><span data-stu-id="5befb-109">Delete a user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetAsync (operations, upnOrObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;GetAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-110">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="5befb-111">Die Objekt-ID oder der Prinzipalname des Benutzers, für den Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="5befb-111">The object ID or principal name of the user for which to get information.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-113">Ruft Benutzerinformationen aus dem Verzeichnis ab.</span><span class="sxs-lookup"><span data-stu-id="5befb-113">Gets user information from the directory.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMemberGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;string&gt;&gt; GetMemberGroupsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string objectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;string&gt;&gt; GetMemberGroupsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string objectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetMemberGroupsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetMemberGroupsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;string&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.GetMemberGroupsAsync (operations, objectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;GetMemberGroupsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="objectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserGetMemberGroupsParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-114">The operations group for this extension method.</span></span>
            </param>
        <param name="objectId">
            <span data-ttu-id="5befb-115">Die Objekt-ID des Benutzers für die Gruppenmitgliedschaft abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5befb-115">The object ID of the user for which to get group membership.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5befb-116">Filterparameter für Benutzer.</span><span class="sxs-lookup"><span data-stu-id="5befb-116">User filtering parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-118">Ruft eine Auflistung, die die Objekt-IDs der Gruppen enthält, von denen der Benutzer Mitglied ist.</span><span class="sxs-lookup"><span data-stu-id="5befb-118">Gets a collection that contains the object IDs of the groups of which the user is a member.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-119">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="5befb-120">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="5befb-120">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-122">Ruft die Liste der Benutzer für den aktuellen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="5befb-122">Gets list of users for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-123">The operations group for this extension method.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5befb-124">Nächsten Link für den List-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5befb-124">Next link for the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-126">Ruft eine Liste von Benutzern für den aktuellen Mandanten an.</span><span class="sxs-lookup"><span data-stu-id="5befb-126">Gets a list of users for the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations operations, string upnOrObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions.UpdateAsync (operations, upnOrObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.UsersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IUsersOperations" RefType="this" />
        <Parameter Name="upnOrObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.UserUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5befb-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5befb-127">The operations group for this extension method.</span></span>
            </param>
        <param name="upnOrObjectId">
            <span data-ttu-id="5befb-128">Die Objekt-ID oder der Prinzipalname des Benutzers aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="5befb-128">The object ID or principal name of the user to update.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5befb-129">Parameter für einen vorhandenen Benutzer zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5befb-129">Parameters to update an existing user.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5befb-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5befb-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5befb-131">Aktualisiert einen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="5befb-131">Updates a user.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>