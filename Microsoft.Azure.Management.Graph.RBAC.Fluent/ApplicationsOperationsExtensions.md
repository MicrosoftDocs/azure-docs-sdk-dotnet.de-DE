<Type Name="ApplicationsOperationsExtensions" FullName="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationsOperationsExtensions = class" />
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
            <span data-ttu-id="3572e-101">Erweiterungsmethoden für ApplicationsOperations.</span><span class="sxs-lookup"><span data-stu-id="3572e-101">Extension methods for ApplicationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; CreateAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; CreateAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.CreateAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;CreateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationCreateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-102">The operations group for this extension method.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3572e-103">Die Parameter zum Erstellen einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="3572e-103">The parameters for creating an application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-105">Erstellen Sie eine neue Anwendung.</span><span class="sxs-lookup"><span data-stu-id="3572e-105">Create a new application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.DeleteAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-106">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-107">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-107">Application object ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-109">Löschen Sie eine Anwendung an.</span><span class="sxs-lookup"><span data-stu-id="3572e-109">Delete an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; GetAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; GetAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.GetAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-110">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-111">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-111">Application object ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-113">Eine Anwendung über den Objekt-ID abrufen</span><span class="sxs-lookup"><span data-stu-id="3572e-113">Get an application by object ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-114">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="3572e-115">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="3572e-115">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-117">Listen-Anwendungen durch Filterparameter aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="3572e-117">Lists applications by filter parameters.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt; ListKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListKeyCredentialsAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListKeyCredentialsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-118">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-119">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-119">Application object ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-121">Rufen Sie die KeyCredentials einer Anwendung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3572e-121">Get the keyCredentials associated with an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string nextLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListNextAsync (operations, nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="3572e-123">Nächsten Link für den List-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3572e-123">Next link for the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-125">Ruft eine Liste der Anwendungen aus dem aktuellen Mandanten ab.</span><span class="sxs-lookup"><span data-stu-id="3572e-125">Gets a list of applications from the current tenant.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt; ListPasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListPasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.ListPasswordCredentialsAsync (operations, applicationObjectId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;ListPasswordCredentialsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredential&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-126">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-127">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-127">Application object ID.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-129">Rufen Sie die PasswordCredentials einer Anwendung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3572e-129">Get the passwordCredentials associated with an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PatchAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PatchAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.PatchAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;PatchAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.ApplicationUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-130">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-131">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-131">Application object ID.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3572e-132">Parameter für eine vorhandene Anwendung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="3572e-132">Parameters to update an existing application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-134">Aktualisieren einer vorhandenen Anwendung an.</span><span class="sxs-lookup"><span data-stu-id="3572e-134">Update an existing application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdateKeyCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdateKeyCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdateKeyCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdateKeyCredentialsAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;UpdateKeyCredentialsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.KeyCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-135">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-136">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-136">Application object ID.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3572e-137">Parameter, die die KeyCredentials einer vorhandenen Anwendung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="3572e-137">Parameters to update the keyCredentials of an existing application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-139">Aktualisieren Sie die KeyCredentials einer Anwendung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3572e-139">Update the keyCredentials associated with an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePasswordCredentialsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpdatePasswordCredentialsAsync (this Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpdatePasswordCredentialsAsync(class Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations operations, string applicationObjectId, class Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdatePasswordCredentialsAsync(Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations,System.String,Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePasswordCredentialsAsync : Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations * string * Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions.UpdatePasswordCredentialsAsync (operations, applicationObjectId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Graph.RBAC.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Graph.RBAC.Fluent.ApplicationsOperationsExtensions/&lt;UpdatePasswordCredentialsAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.IApplicationsOperations" RefType="this" />
        <Parameter Name="applicationObjectId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Graph.RBAC.Fluent.Models.PasswordCredentialsUpdateParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3572e-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3572e-140">The operations group for this extension method.</span></span>
            </param>
        <param name="applicationObjectId">
            <span data-ttu-id="3572e-141">Anwendungsobjekt-ID</span><span class="sxs-lookup"><span data-stu-id="3572e-141">Application object ID.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3572e-142">Parameter PasswordCredentials einer vorhandenen Anwendung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="3572e-142">Parameters to update passwordCredentials of an existing application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3572e-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3572e-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3572e-144">Aktualisieren Sie PasswordCredentials einer Anwendung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3572e-144">Update passwordCredentials associated with an application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>