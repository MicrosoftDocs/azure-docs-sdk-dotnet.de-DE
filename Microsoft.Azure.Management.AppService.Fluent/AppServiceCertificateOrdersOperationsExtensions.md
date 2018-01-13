<Type Name="AppServiceCertificateOrdersOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AppServiceCertificateOrdersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AppServiceCertificateOrdersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AppServiceCertificateOrdersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5a0b4-101">Erweiterungsmethoden für AppServiceCertificateOrdersOperations.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-101">Extension methods for AppServiceCertificateOrdersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-104">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-104">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="5a0b4-105">Distinguished Name, um für die Bestellung Zertifikat verwenden.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-105">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-107">Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-107">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-108">Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-108">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; BeginCreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.BeginCreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;BeginCreateOrUpdateCertificateAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-110">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-111">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-111">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-112">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-112">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="5a0b4-113">Ressourcen-ID für Key Vault-Zertifikat</span><span class="sxs-lookup"><span data-stu-id="5a0b4-113">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-115">Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-115">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-116">Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-116">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner certificateDistinguishedName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, certificateOrderName, certificateDistinguishedName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="certificateDistinguishedName" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-118">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-118">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-119">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-119">Name of the certificate order.</span></span>
            </param>
        <param name="certificateDistinguishedName">
            <span data-ttu-id="5a0b4-120">Distinguished Name, um für die Bestellung Zertifikat verwenden.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-120">Distinguished name to to use for the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-122">Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-122">Create or update a certificate purchase order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-123">Erstellen Sie oder aktualisieren Sie ein Zertifikat PurchaseOrder-Objekt.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-123">Create or update a certificate purchase order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; CreateOrUpdateCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner keyVaultCertificate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.CreateOrUpdateCertificateAsync (operations, resourceGroupName, certificateOrderName, name, keyVaultCertificate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;CreateOrUpdateCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keyVaultCertificate" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-125">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-125">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-126">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-126">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-127">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-127">Name of the certificate.</span></span>
            </param>
        <param name="keyVaultCertificate">
            <span data-ttu-id="5a0b4-128">Ressourcen-ID für Key Vault-Zertifikat</span><span class="sxs-lookup"><span data-stu-id="5a0b4-128">Key vault certificate resource Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-130">Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-130">Creates or updates a certificate and associates with key vault secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-131">Erstellt oder aktualisiert ein Zertifikat, und ordnet schlüsseltresor geheime Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-131">Creates or updates a certificate and associates with key vault secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-133">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-133">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-134">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-134">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-136">Löschen eines vorhandenen Zertifikats-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-136">Delete an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-137">Löschen eines vorhandenen Zertifikats-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-137">Delete an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.DeleteCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;DeleteCertificateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-139">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-139">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-140">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-140">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-141">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-141">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-143">Löschen Sie das Zertifikat mit einem Zertifikat zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-143">Delete the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-144">Löschen Sie das Zertifikat mit einem Zertifikat zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-144">Delete the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt; GetAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-146">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-146">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-147">Der Name des Auftrags Zertifikat...</span><span class="sxs-lookup"><span data-stu-id="5a0b4-147">Name of the certificate order..</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-149">Abrufen einer zertifikatreihenfolge an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-149">Get a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-150">Abrufen einer zertifikatreihenfolge an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-150">Get a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt; GetCertificateAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.GetCertificateAsync (operations, resourceGroupName, certificateOrderName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;GetCertificateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-152">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-152">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-153">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-153">Name of the certificate order.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-154">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-154">Name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-156">Abrufen einer zertifikatreihenfolge zugeordneten Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-156">Get the certificate associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-157">Abrufen einer zertifikatreihenfolge zugeordneten Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-157">Get the certificate associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-158">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-160">Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-160">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-161">Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-161">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-163">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-163">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-165">Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-165">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-166">Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-166">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-167">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5a0b4-168">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-168">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-170">Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-170">Get certificate orders in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-171">Abrufen von Zertifikat Aufträge in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-171">Get certificate orders in a resource group.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-173">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-173">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-174">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-174">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-176">Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-176">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-177">Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-177">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt; ListCertificatesNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListCertificatesNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListCertificatesNextAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateResourceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-178">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5a0b4-179">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-181">Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-181">List all certificates associated with a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-182">Listen Sie alle zugeordneten Zertifikate für eine zertifikatreihenfolge.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-182">List all certificates associated with a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ListNextAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5a0b4-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-186">Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-186">List all certificate orders in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-187">Listen Sie aller Zertifikat Bestellungen in einem Abonnement an auf.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-187">List all certificate orders in a subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReissueAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ReissueAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ReissueAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner reissueCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReissueAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ReissueAsync (operations, resourceGroupName, certificateOrderName, reissueCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ReissueAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="reissueCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ReissueCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-189">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-189">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-190">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-190">Name of the certificate order.</span></span>
            </param>
        <param name="reissueCertificateOrderRequest">
            <span data-ttu-id="5a0b4-191">Parameter für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-191">Parameters for the reissue.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-193">Geben Sie eine vorhandene zertifikatreihenfolge erneut aus.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-193">Reissue an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-194">Geben Sie eine vorhandene zertifikatreihenfolge erneut aus.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-194">Reissue an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RenewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RenewAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RenewAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner renewCertificateOrderRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RenewAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RenewAsync (operations, resourceGroupName, certificateOrderName, renewCertificateOrderRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RenewAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="renewCertificateOrderRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.RenewCertificateOrderRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-196">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-196">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-197">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-197">Name of the certificate order.</span></span>
            </param>
        <param name="renewCertificateOrderRequest">
            <span data-ttu-id="5a0b4-198">Erneuern von Parametern</span><span class="sxs-lookup"><span data-stu-id="5a0b4-198">Renew parameters</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-200">Erneuern eines vorhandenen Zertifikats-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-200">Renew an existing certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-201">Erneuern eines vorhandenen Zertifikats-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-201">Renew an existing certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendEmailAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendEmailAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendEmailAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendEmailAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendEmailAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendEmailAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-203">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-203">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-204">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-204">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-205">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-206">Senden Sie Zertifikat e-Mail erneut.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-206">Resend certificate email.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-207">Senden Sie Zertifikat e-Mail erneut.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-207">Resend certificate email.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResendRequestEmailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResendRequestEmailsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResendRequestEmailsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner nameIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResendRequestEmailsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ResendRequestEmailsAsync (operations, resourceGroupName, certificateOrderName, nameIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ResendRequestEmailsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="nameIdentifier" Type="Microsoft.Azure.Management.AppService.Fluent.Models.NameIdentifierInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="certificateOrderName">To be added.</param>
        <param name="nameIdentifier">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateActionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt; RetrieveCertificateActionsAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateActionsAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateActionsAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateActionsAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderActionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-208">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-209">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-209">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-210">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-210">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-211">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-211">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-212">Die Liste der Aktionen Zertifikat abrufen.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-212">Retrieve the list of certificate actions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-213">Die Liste der Aktionen Zertifikat abrufen.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-213">Retrieve the list of certificate actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveCertificateEmailHistoryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt; RetrieveCertificateEmailHistoryAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveCertificateEmailHistoryAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveCertificateEmailHistoryAsync (operations, resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveCertificateEmailHistoryAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateEmailInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-215">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="5a0b4-216">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-216">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-217">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-217">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-218">Abgerufen Sie e-Mail-Verlauf werden.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-218">Retrieve email history.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-219">Abgerufen Sie e-Mail-Verlauf werden.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-219">Retrieve email history.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveSiteSealAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt; RetrieveSiteSealAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner siteSealRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveSiteSealAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.RetrieveSiteSealAsync (operations, resourceGroupName, certificateOrderName, siteSealRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;RetrieveSiteSealAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="siteSealRequest" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteSealRequestInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-221">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-221">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-222">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-222">Name of the certificate order.</span></span>
            </param>
        <param name="siteSealRequest">
            <span data-ttu-id="5a0b4-223">Standort versiegeln-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-223">Site seal request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-224">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-225">Domänenbesitz für diesen Auftrag Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-225">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-226">Domänenbesitz für diesen Auftrag Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-226">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidatePurchaseInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidatePurchaseInformationAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidatePurchaseInformationAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner appServiceCertificateOrder, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidatePurchaseInformationAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.ValidatePurchaseInformationAsync (operations, appServiceCertificateOrder, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;ValidatePurchaseInformationAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="appServiceCertificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-227">The operations group for this extension method.</span></span>
            </param>
        <param name="appServiceCertificateOrder">
            <span data-ttu-id="5a0b4-228">Informationen für eine Bestellung Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-228">Information for a certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-229">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-229">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-230">Für eine Bestellung Zertifikat zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-230">Validate information for a certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-231">Für eine Bestellung Zertifikat zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-231">Validate information for a certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task VerifyDomainOwnershipAsync (this Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations operations, string resourceGroupName, string certificateOrderName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions.VerifyDomainOwnershipAsync (operations, resourceGroupName, certificateOrderName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrdersOperationsExtensions/&lt;VerifyDomainOwnershipAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrdersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5a0b4-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5a0b4-233">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-233">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="certificateOrderName">
            <span data-ttu-id="5a0b4-234">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-234">Name of the certificate order.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a0b4-235">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a0b4-236">Domänenbesitz für diesen Auftrag Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-236">Verify domain ownership for this certificate order.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="5a0b4-237">Domänenbesitz für diesen Auftrag Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="5a0b4-237">Verify domain ownership for this certificate order.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>