<Type Name="ApplicationPackageOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ApplicationPackageOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ApplicationPackageOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ApplicationPackageOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ed282-101">Erweiterungsmethoden für ApplicationPackageOperations.</span><span class="sxs-lookup"><span data-stu-id="ed282-101">Extension methods for ApplicationPackageOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ActivateAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ActivateAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, class Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.ActivateAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ActivateAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.ActivateAsync (operations, resourceGroupName, accountName, applicationId, version, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;ActivateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Batch.Fluent.Models.ActivateApplicationPackageParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="accountName">To be added.</param>
        <param name="applicationId">To be added.</param>
        <param name="version">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; CreateAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; CreateAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.CreateAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed282-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ed282-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed282-103">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ed282-103">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ed282-104">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="ed282-104">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="ed282-105">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ed282-105">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="ed282-106">Die Version der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ed282-106">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ed282-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ed282-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed282-108">Erstellt einen Anwendung Paket Datensatz.</span><span class="sxs-lookup"><span data-stu-id="ed282-108">Creates an application package record.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.DeleteAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed282-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ed282-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed282-110">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ed282-110">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ed282-111">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="ed282-111">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="ed282-112">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ed282-112">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="ed282-113">Die Version der Anwendung, die gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ed282-113">The version of the application to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ed282-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ed282-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed282-115">Löscht Anwendungsdatensatz Paket und dessen zugeordnete Binärdatei.</span><span class="sxs-lookup"><span data-stu-id="ed282-115">Deletes an application package record and its associated binary file.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; GetAsync (this Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt; GetAsync(class Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations operations, string resourceGroupName, string accountName, string applicationId, string version, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.GetAsync(Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions.GetAsync (operations, resourceGroupName, accountName, applicationId, version, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.ApplicationPackageOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.ApplicationPackageInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.IApplicationPackageOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="applicationId" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ed282-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ed282-116">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ed282-117">Der Name der Ressourcengruppe, die das Batch-Konto enthält.</span><span class="sxs-lookup"><span data-stu-id="ed282-117">The name of the resource group that contains the Batch account.</span></span>
            </param>
        <param name="accountName">
            <span data-ttu-id="ed282-118">Der Name des Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="ed282-118">The name of the Batch account.</span></span>
            </param>
        <param name="applicationId">
            <span data-ttu-id="ed282-119">Die ID der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ed282-119">The ID of the application.</span></span>
            </param>
        <param name="version">
            <span data-ttu-id="ed282-120">Die Version der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ed282-120">The version of the application.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ed282-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ed282-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ed282-122">Ruft Informationen zum angegebenen Anwendungspaket ab.</span><span class="sxs-lookup"><span data-stu-id="ed282-122">Gets information about the specified application package.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>