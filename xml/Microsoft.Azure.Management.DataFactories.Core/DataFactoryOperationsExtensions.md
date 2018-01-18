<Type Name="DataFactoryOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataFactoryOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataFactoryOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataFactoryOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataFactoryOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-102">Required.</span></span> <span data-ttu-id="3419c-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3419c-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-104">Required.</span></span> <span data-ttu-id="3419c-105">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-105">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-106">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-106">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-107">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-107">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-108">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-108">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-109">Required.</span></span> <span data-ttu-id="3419c-110">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-110">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3419c-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-111">Required.</span></span> <span data-ttu-id="3419c-112">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-112">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-113">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-113">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-114">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-114">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-115">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-115">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-116">Required.</span></span> <span data-ttu-id="3419c-117">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-117">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3419c-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-118">Required.</span></span> <span data-ttu-id="3419c-119">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-119">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-120">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-120">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-121">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-121">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDataFactoryOperations, resourceGroupName As String, parameters As DataFactoryCreateOrUpdateParameters) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-122">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-122">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-123">Required.</span></span> <span data-ttu-id="3419c-124">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-124">The resource group name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3419c-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-125">Required.</span></span> <span data-ttu-id="3419c-126">Die Parameter zum Erstellen oder Aktualisieren einer Data Factory erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-126">The parameters required to create or update a data factory.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-127">Erstellen oder Aktualisieren einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-127">Create or update a data factory.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-128">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-128">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-129">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-129">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-130">Required.</span></span> <span data-ttu-id="3419c-131">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-131">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="3419c-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-132">Required.</span></span> <span data-ttu-id="3419c-133">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="3419c-133">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-134">Löschen Sie eine Data Factory-Instanz.</span><span class="sxs-lookup"><span data-stu-id="3419c-134">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-135">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="3419c-135">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-136">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-136">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-137">Required.</span></span> <span data-ttu-id="3419c-138">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-138">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="3419c-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-139">Required.</span></span> <span data-ttu-id="3419c-140">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="3419c-140">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-141">Löschen Sie eine Data Factory-Instanz.</span><span class="sxs-lookup"><span data-stu-id="3419c-141">Delete a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-142">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="3419c-142">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As DataFactoryGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-143">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-143">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-144">Required.</span></span> <span data-ttu-id="3419c-145">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-145">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="3419c-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-146">Required.</span></span> <span data-ttu-id="3419c-147">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="3419c-147">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-148">Ruft eine Instanz einer Factory ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-148">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-149">Get Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-149">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDataFactoryOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DataFactoryGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-150">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-151">Required.</span></span> <span data-ttu-id="3419c-152">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="3419c-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="3419c-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-153">Required.</span></span> <span data-ttu-id="3419c-154">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="3419c-154">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-155">Ruft eine Instanz einer Factory ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-155">Gets a data factory instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-156">Get Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-156">The Get data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDataFactoryOperations, operationStatusLink As String) As DataFactoryCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-157">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-157">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="3419c-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-158">Required.</span></span> <span data-ttu-id="3419c-159">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3419c-159">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-160">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="3419c-160">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="3419c-161">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="3419c-161">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-162">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-162">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDataFactoryOperations, operationStatusLink As String) As Task(Of DataFactoryCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-163">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-163">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="3419c-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-164">Required.</span></span> <span data-ttu-id="3419c-165">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="3419c-165">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-166">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="3419c-166">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="3419c-167">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="3419c-167">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-168">Erstellen oder aktualisieren Data Factory Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-168">The create or update data factory operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataFactoryOperations, resourceGroupName As String) As DataFactoryListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-169">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-169">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-170">Required.</span></span> <span data-ttu-id="3419c-171">Der Ressourcengruppenname von Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="3419c-171">The resource group name of the data factories.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-172">Ruft die erste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-172">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-173">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-173">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataFactoryOperations, resourceGroupName As String) As Task(Of DataFactoryListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-174">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-174">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3419c-175">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-175">Required.</span></span> <span data-ttu-id="3419c-176">Der Ressourcengruppenname von Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="3419c-176">The resource group name of the data factories.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-177">Ruft die erste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-177">Gets the first page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-178">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-178">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataFactoryOperations, nextLink As String) As DataFactoryListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-179">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-179">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="3419c-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-180">Required.</span></span> <span data-ttu-id="3419c-181">Die Url mit der nächsten Seite des Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="3419c-181">The url to the next data factories page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-182">Ruft die nächste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-182">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-183">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-183">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataFactoryOperations, nextLink As String) As Task(Of DataFactoryListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataFactoryOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataFactoryListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3419c-184">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span><span class="sxs-lookup"><span data-stu-id="3419c-184">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataFactoryOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="3419c-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="3419c-185">Required.</span></span> <span data-ttu-id="3419c-186">Die Url mit der nächsten Seite des Data-Factorys.</span><span class="sxs-lookup"><span data-stu-id="3419c-186">The url to the next data factories page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3419c-187">Ruft die nächste Seite der Data Factory-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="3419c-187">Gets the next page of data factory instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3419c-188">Liste Data Factorys Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3419c-188">The List data factories operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>