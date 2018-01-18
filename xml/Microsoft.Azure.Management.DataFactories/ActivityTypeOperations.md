<Type Name="ActivityTypeOperations" FullName="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations">
  <TypeSignature Language="C#" Value="public class ActivityTypeOperations : Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityTypeOperations extends System.Object implements class Hyak.Common.IServiceOperations`1&lt;class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;, class Microsoft.Azure.Management.DataFactories.IActivityTypeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityTypeOperations&#xA;Implements IActivityTypeOperations, IServiceOperations(Of DataFactoryManagementClient)" />
  <TypeSignature Language="F#" Value="type ActivityTypeOperations = class&#xA;    interface IServiceOperations&lt;DataFactoryManagementClient&gt;&#xA;    interface IActivityTypeOperations" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Hyak.Common.IServiceOperations&lt;Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.IActivityTypeOperations</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cf67d-101">Vorgänge zum Verwalten von Data Factory "activitytypes".</span><span class="sxs-lookup"><span data-stu-id="cf67d-101">Operations for managing data factory ActivityTypes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-102">Required.</span></span> <span data-ttu-id="cf67d-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-104">Required.</span></span> <span data-ttu-id="cf67d-105">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-105">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="cf67d-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-106">Required.</span></span> <span data-ttu-id="cf67d-107">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="cf67d-107">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-108">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-108">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-109">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="cf67d-109">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-110">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="cf67d-110">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Client">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient Client" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Client As DataFactoryManagementClient" />
      <MemberSignature Language="F#" Value="member this.Client : Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient" Usage="Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.Client" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.DataFactoryManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-111">Required.</span></span> <span data-ttu-id="cf67d-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-113">Required.</span></span> <span data-ttu-id="cf67d-114">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-114">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf67d-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-115">Required.</span></span> <span data-ttu-id="cf67d-116">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-116">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-117">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-118">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="cf67d-118">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-119">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cf67d-119">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;&#xA;override this.CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;" Usage="activityTypeOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, activityTypeName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;CreateOrUpdateWithRawJsonContentAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-120">Required.</span></span> <span data-ttu-id="cf67d-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-122">Required.</span></span> <span data-ttu-id="cf67d-123">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-123">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="cf67d-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-124">Required.</span></span> <span data-ttu-id="cf67d-125">Der Name einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="cf67d-125">An ActivityType name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf67d-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-126">Required.</span></span> <span data-ttu-id="cf67d-127">Die Parameter zum Erstellen oder Aktualisieren einer ActivityType-Definition erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-127">The parameters required to create or update an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-128">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-129">Erstellen Sie oder aktualisieren Sie einer ActivityType.</span><span class="sxs-lookup"><span data-stu-id="cf67d-129">Create or update an ActivityType.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-130">Erstellen oder aktualisieren ActivityType Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cf67d-130">The create or update ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string activityTypeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string activityTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;&#xA;override this.DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="activityTypeOperations.DeleteAsync (resourceGroupName, dataFactoryName, activityTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;DeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="activityTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-131">Required.</span></span> <span data-ttu-id="cf67d-132">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-133">Required.</span></span> <span data-ttu-id="cf67d-134">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-134">The name of the data factory.</span></span>
            </param>
        <param name="activityTypeName">
            <span data-ttu-id="cf67d-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-135">Required.</span></span> <span data-ttu-id="cf67d-136">Der Name des der ActivityType.</span><span class="sxs-lookup"><span data-stu-id="cf67d-136">The name of the activityType.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-137">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-138">Löschen einer ActivityType-Instanz.</span><span class="sxs-lookup"><span data-stu-id="cf67d-138">Delete an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-139">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="cf67d-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;&#xA;override this.GetAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;" Usage="activityTypeOperations.GetAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.GetAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeGetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-140">Required.</span></span> <span data-ttu-id="cf67d-141">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-141">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-142">Required.</span></span> <span data-ttu-id="cf67d-143">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-143">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf67d-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-144">Required.</span></span> <span data-ttu-id="cf67d-145">Parameter, die zum Abrufen einer ActivityType-Definition angibt.</span><span class="sxs-lookup"><span data-stu-id="cf67d-145">Parameters specifying how to get an ActivityType definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-146">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-147">Ruft eine ActivityType-Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="cf67d-147">Gets an ActivityType instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-148">Die ActivityType Get Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="cf67d-148">The Get ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListAsync : string * string * Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="cf67d-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-149">Required.</span></span> <span data-ttu-id="cf67d-150">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="cf67d-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-151">Required.</span></span> <span data-ttu-id="cf67d-152">Der Name der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="cf67d-152">The name of the data factory.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cf67d-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-153">Required.</span></span> <span data-ttu-id="cf67d-154">Parameter, die angibt, wie eine Liste der ActivityType-Definitionen zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="cf67d-154">Parameters specifying how to return a list of ActivityType definitions.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-155">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-156">Ruft die erste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="cf67d-156">Gets the first page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-157">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="cf67d-157">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.ActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;&#xA;override this.ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;" Usage="activityTypeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.DataFactories.IActivityTypeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.DataFactories.ActivityTypeOperations/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Registration.Models.ActivityTypeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="cf67d-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="cf67d-158">Required.</span></span> <span data-ttu-id="cf67d-159">Die Url zur nächsten Seite "activitytypes".</span><span class="sxs-lookup"><span data-stu-id="cf67d-159">The url to the next ActivityTypes page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cf67d-160">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cf67d-160">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cf67d-161">Ruft die nächste Seite der ActivityType-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="cf67d-161">Gets the next page of ActivityType instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="cf67d-162">Die Liste ActivityType Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="cf67d-162">The List ActivityType operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>