<Type Name="IHardwareComponentGroupsOperations" FullName="Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations">
  <TypeSignature Language="C#" Value="public interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHardwareComponentGroupsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHardwareComponentGroupsOperations" />
  <TypeSignature Language="F#" Value="type IHardwareComponentGroupsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdaa8-101">HardwareComponentGroupsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-101">HardwareComponentGroupsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; BeginChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.BeginChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="fdaa8-102">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="fdaa8-102">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="fdaa8-103">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-103">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fdaa8-104">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-104">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdaa8-105">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="fdaa8-105">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="fdaa8-106">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="fdaa8-106">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fdaa8-107">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdaa8-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdaa8-109">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-109">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fdaa8-110">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-110">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fdaa8-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ChangeControllerPowerStateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync (string deviceName, string hardwareComponentGroupName, Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ChangeControllerPowerStateWithHttpMessagesAsync(string deviceName, string hardwareComponentGroupName, class Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest parameters, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeControllerPowerStateWithHttpMessagesAsync : string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iHardwareComponentGroupsOperations.ChangeControllerPowerStateWithHttpMessagesAsync (deviceName, hardwareComponentGroupName, parameters, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="hardwareComponentGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ControllerPowerStateChangeRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="fdaa8-112">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="fdaa8-112">The device name</span></span>
            </param>
        <param name="hardwareComponentGroupName">
            <span data-ttu-id="fdaa8-113">Der Gruppenname der Hardware-Komponente.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-113">The hardware component group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fdaa8-114">Der Zustand des Controllers Power-änderungsanforderung.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-114">The controller power state change request.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdaa8-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="fdaa8-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="fdaa8-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="fdaa8-116">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fdaa8-117">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-117">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdaa8-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdaa8-119">Ändert den Energiezustand des Controllers an.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-119">Changes the power state of the controller.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fdaa8-120">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-120">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fdaa8-121">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-121">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync (string deviceName, string resourceGroupName, string managerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt; ListByDeviceWithHttpMessagesAsync(string deviceName, string resourceGroupName, string managerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.IHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDeviceWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;" Usage="iHardwareComponentGroupsOperations.ListByDeviceWithHttpMessagesAsync (deviceName, resourceGroupName, managerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.HardwareComponentGroup&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceName">
            <span data-ttu-id="fdaa8-122">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="fdaa8-122">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fdaa8-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="fdaa8-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="fdaa8-124">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="fdaa8-124">The manager name</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fdaa8-125">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-125">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fdaa8-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fdaa8-127">Listet die Komponentengruppen Hardware auf Geräteebene.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-127">Lists the hardware component groups at device-level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="fdaa8-128">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-128">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="fdaa8-129">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-129">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fdaa8-130">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="fdaa8-130">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>