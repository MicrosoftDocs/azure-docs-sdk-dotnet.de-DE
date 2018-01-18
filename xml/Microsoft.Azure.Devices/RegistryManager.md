<Type Name="RegistryManager" FullName="Microsoft.Azure.Devices.RegistryManager">
  <TypeSignature Language="C#" Value="public abstract class RegistryManager : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RegistryManager extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.RegistryManager" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RegistryManager&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type RegistryManager = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f470b-101">Enthält Methoden, die Dienste verwenden können, auszuführenden erstellen, entfernen, update und delete-Vorgänge auf Geräten.</span><span class="sxs-lookup"><span data-stu-id="f470b-101">Contains methods that services can use to perform create, remove, update and delete operations on devices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RegistryManager ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-102">Das Objekt registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-102">The Device object to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-103">Registrieren Sie ein neues Gerät mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-103">Register a new device with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-104">wiederholt zurück, das Objekt mit dem generierten Schlüsseln und etags</span><span class="sxs-lookup"><span data-stu-id="f470b-104">echoes back the Device object with the generated keys and etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-105">Das Objekt registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-105">The Device object to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-106">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-106">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-107">Registrieren Sie ein neues Gerät mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-107">Register a new device with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-108">wiederholt zurück, das Objekt mit dem generierten Schlüsseln und etags</span><span class="sxs-lookup"><span data-stu-id="f470b-108">echoes back the Device object with the generated keys and etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-109">Geräteobjekte registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-109">The Device objects to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-110">Registrieren Sie eine Liste neuer Geräte mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-110">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-111">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-111">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-112">Geräteobjekte registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-112">The Device objects to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-113">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-113">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-114">Registrieren Sie eine Liste neuer Geräte mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-114">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-115">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-115">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-116">Geräteobjekte registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-116">The Device objects to be registered.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-117">Registrieren Sie eine Liste neuer Geräte mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-117">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-118">Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</span><span class="sxs-lookup"><span data-stu-id="f470b-118">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-119">Geräteobjekte registriert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-119">The Device objects to be registered.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-120">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-120">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-121">Registrieren Sie eine Liste neuer Geräte mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-121">Register a list of new devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-122">Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</span><span class="sxs-lookup"><span data-stu-id="f470b-122">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="f470b-123">ID des Auftrags auf "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="f470b-123">Id of the Job to cancel</span></span></param>
        <summary>
            <span data-ttu-id="f470b-124">Bricht/löscht den Auftrag mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="f470b-124">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="f470b-125">ID des Auftrags auf "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="f470b-125">Id of the job to cancel</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-126">Aufgabenabbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-126">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-127">Bricht/löscht den Auftrag mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="f470b-127">Cancels/Deletes the job with the specified ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f470b-128">Schließt die RegistryManager-Instanz, und seine Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="f470b-128">Closes the RegistryManager instance and disposes its resources.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As RegistryManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.RegistryManager" Usage="Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.RegistryManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> <span data-ttu-id="f470b-129">Der Iot Hub-Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="f470b-129">The Iot Hub connection string.</span></span></param>
        <summary>
            <span data-ttu-id="f470b-130">Erstellt eine RegistryManager aus der Iot Hub-Verbindungszeichenfolge an.</span><span class="sxs-lookup"><span data-stu-id="f470b-130">Creates a RegistryManager from the Iot Hub connection string.</span></span>
            </summary>
        <returns> <span data-ttu-id="f470b-131">Eine RegistryManager-Instanz.</span><span class="sxs-lookup"><span data-stu-id="f470b-131">An RegistryManager instance.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery sqlQueryString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <summary>
            <span data-ttu-id="f470b-132">Ruft ein Handle, das über die ein Ergebnis für eine bestimmte Abfrage abgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f470b-132">Retrieves a handle through which a result for a given query can be fetched.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String, pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery (sqlQueryString, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <param name="pageSize"></param>
        <summary>
            <span data-ttu-id="f470b-133">Ruft ein Handle, das über die ein Ergebnis für eine bestimmte Abfrage abgerufen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f470b-133">Retrieves a handle through which a result for a given query can be fetched.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="registryManager.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="registryManager.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <span data-ttu-id="f470b-134"><c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</span><span class="sxs-lookup"><span data-stu-id="f470b-134"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="f470b-135">Nicht verwaltete und optional verwaltete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="f470b-135">Releases unmanaged and - optionally - managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"><span data-ttu-id="f470b-136">Ziel-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-136">Destination blob container URI</span></span></param>
        <param name="excludeKeys"><span data-ttu-id="f470b-137">Gibt an, ob das Gerät Schlüssel während des Exports ausschließen</span><span class="sxs-lookup"><span data-stu-id="f470b-137">Specifies whether to exclude the Device's Keys during the export</span></span></param>
        <summary>
            <span data-ttu-id="f470b-138">Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="f470b-138">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-139">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-139">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"><span data-ttu-id="f470b-140">Ziel-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-140">Destination blob container URI</span></span></param>
        <param name="excludeKeys"><span data-ttu-id="f470b-141">Gibt an, ob das Gerät Schlüssel während des Exports ausschließen</span><span class="sxs-lookup"><span data-stu-id="f470b-141">Specifies whether to exclude the Device's Keys during the export</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-142">Aufgabenabbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-142">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-143">Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="f470b-143">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-144">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-144">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, outputBlobName As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <summary>
            <span data-ttu-id="f470b-145">Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="f470b-145">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-146">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-146">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="f470b-147">Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="f470b-147">Creates a new bulk job to export device registrations to the container specified by the provided URI.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-148">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-148">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDeviceAsync (deviceId As String) As Task(Of Device)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="f470b-149">Die Id des Geräts abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f470b-149">The id of the device to be retrieved.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-150">Ruft das angegebene Objekt ab.</span><span class="sxs-lookup"><span data-stu-id="f470b-150">Retrieves the specified Device object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f470b-151">Das Gerät-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f470b-151">The Device object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="f470b-152">Die Id des Geräts abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f470b-152">The id of the device to be retrieved.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-153">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-153">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-154">Ruft das angegebene Objekt ab.</span><span class="sxs-lookup"><span data-stu-id="f470b-154">Retrieves the specified Device object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f470b-155">Das Gerät-Objekt.</span><span class="sxs-lookup"><span data-stu-id="f470b-155">The Device object.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDevicesAsync (maxCount As Integer) As Task(Of IEnumerable(Of Device))" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <summary>
            <span data-ttu-id="f470b-156">Ruft die angegebene Anzahl von Geräten aus jeder Iot Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="f470b-156">Retrieves specified number of devices from every Iot Hub partition.</span></span> <span data-ttu-id="f470b-157">Dies ist eine Näherung darstellt und nicht auf eine endgültige Liste.</span><span class="sxs-lookup"><span data-stu-id="f470b-157">This is an approximation and not a definitive list.</span></span> <span data-ttu-id="f470b-158">Ergebnisse werden nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="f470b-158">Results are not ordered.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f470b-159">Die Liste der Geräte</span><span class="sxs-lookup"><span data-stu-id="f470b-159">The list of devices</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync (maxCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f470b-160">Ruft die angegebene Anzahl von Geräten aus jeder Iot Hub-Partition.</span><span class="sxs-lookup"><span data-stu-id="f470b-160">Retrieves specified number of devices from every Iot hub partition.</span></span> <span data-ttu-id="f470b-161">Dies ist eine Näherung darstellt und nicht auf eine endgültige Liste.</span><span class="sxs-lookup"><span data-stu-id="f470b-161">This is an approximation and not a definitive list.</span></span> <span data-ttu-id="f470b-162">Ergebnisse werden nicht sortiert.</span><span class="sxs-lookup"><span data-stu-id="f470b-162">Results are not ordered.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f470b-163">Die Liste der Geräte</span><span class="sxs-lookup"><span data-stu-id="f470b-163">The list of devices</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="f470b-164">Die ID des Objekts Auftrag abrufen</span><span class="sxs-lookup"><span data-stu-id="f470b-164">Id of the Job object to retrieve</span></span></param>
        <summary>
            <span data-ttu-id="f470b-165">Ruft den Auftrag mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="f470b-165">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-166">JobProperties des Auftrags durch die bereitgestellten "JobID"-Wert angegeben.</span><span class="sxs-lookup"><span data-stu-id="f470b-166">JobProperties of the job specified by the provided jobId.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId"><span data-ttu-id="f470b-167">Die ID des Objekts Auftrag abrufen</span><span class="sxs-lookup"><span data-stu-id="f470b-167">Id of the Job object to retrieve</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-168">Aufgabenabbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-168">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-169">Ruft den Auftrag mit der angegebenen ID.</span><span class="sxs-lookup"><span data-stu-id="f470b-169">Gets the job with the specified ID.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-170">JobProperties des Auftrags durch die bereitgestellten "JobID"-Wert angegeben.</span><span class="sxs-lookup"><span data-stu-id="f470b-170">JobProperties of the job specified by the provided jobId.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobsAsync () As Task(Of IEnumerable(Of JobProperties))" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f470b-171">Führt alle Aufträgen für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-171">List all jobs for the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-172">IEnumerable von JobProperties aller Aufträge für diese IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-172">IEnumerable of JobProperties of all jobs for this IoT Hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="f470b-173">Aufgabenabbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-173">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-174">Führt alle Aufträgen für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-174">List all jobs for the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-175">IEnumerable von JobProperties aller Aufträge für diese IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-175">IEnumerable of JobProperties of all jobs for this IoT Hub.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetRegistryStatisticsAsync () As Task(Of RegistryStatistics)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f470b-176">Ruft die von den Nutzungsstatistiken für Iot Hub ab.</span><span class="sxs-lookup"><span data-stu-id="f470b-176">Gets usage statistics for the Iot Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-177">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-177">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-178">Ruft die von den Nutzungsstatistiken für Iot Hub ab.</span><span class="sxs-lookup"><span data-stu-id="f470b-178">Gets usage statistics for the Iot Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTwinAsync (deviceId As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-179">Geräte-Id</span><span class="sxs-lookup"><span data-stu-id="f470b-179">device Id</span></span></param>
        <summary>
            <span data-ttu-id="f470b-180">Ruft <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> aus IotHub</span><span class="sxs-lookup"><span data-stu-id="f470b-180">Gets <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> from IotHub</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-181">Ziel-Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-181">Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-182">Geräte-Id</span><span class="sxs-lookup"><span data-stu-id="f470b-182">device Id</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-183">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-183">cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-184">Ruft <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> aus IotHub</span><span class="sxs-lookup"><span data-stu-id="f470b-184">Gets <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> from IotHub</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-185">Ziel-Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-185">Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"><span data-ttu-id="f470b-186">Quell-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-186">Source blob container URI</span></span></param>
        <param name="outputBlobContainerUri"><span data-ttu-id="f470b-187">Ziel-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-187">Destination blob container URI</span></span></param>
        <summary>
            <span data-ttu-id="f470b-188">Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-188">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-189">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-189">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String, inputBlobName As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <summary>
            <span data-ttu-id="f470b-190">Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-190">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-191">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-191">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"><span data-ttu-id="f470b-192">Quell-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-192">Source blob container URI</span></span></param>
        <param name="outputBlobContainerUri"><span data-ttu-id="f470b-193">Ziel-BLOB-Container-URI</span><span class="sxs-lookup"><span data-stu-id="f470b-193">Destination blob container URI</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-194">Aufgabenabbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-194">Task cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-195">Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-195">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-196">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-196">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="f470b-197">Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="f470b-197">Creates a new bulk job to import device registrations into the IoT Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-198">JobProperties des neu erstellten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f470b-198">JobProperties of the newly created job.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f470b-199">Öffnen Sie explizit die RegistryManager-Instanz.</span><span class="sxs-lookup"><span data-stu-id="f470b-199">Explicitly open the RegistryManager instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-200">Das Gerät gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f470b-200">The device to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-201">Löscht einen zuvor registrierten Gerät aus dem System.</span><span class="sxs-lookup"><span data-stu-id="f470b-201">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDeviceAsync (deviceId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="f470b-202">Die Id des Geräts gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f470b-202">The id of the device to be deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-203">Löscht einen zuvor registrierten Gerät aus dem System.</span><span class="sxs-lookup"><span data-stu-id="f470b-203">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-204">Das Gerät gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f470b-204">The device to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-205">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-205">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-206">Löscht einen zuvor registrierten Gerät aus dem System.</span><span class="sxs-lookup"><span data-stu-id="f470b-206">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="f470b-207">Die Id des Geräts gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="f470b-207">The id of the device to be deleted.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-208">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-208">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-209">Löscht einen zuvor registrierten Gerät aus dem System.</span><span class="sxs-lookup"><span data-stu-id="f470b-209">Deletes a previously registered device from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-210">Die Geräte, die gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-210">The devices being deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-211">Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f470b-211">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-212">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-212">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-213">Die Geräte, die gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-213">The devices being deleted.</span></span>
            </param>
        <param name="forceRemove">
            <span data-ttu-id="f470b-214">Erzwingt, dass das Objekt entfernt werden soll, selbst wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-214">Forces the device object to be removed even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-215">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-215">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-216">Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f470b-216">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-217">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-217">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-218">Die Geräte, die gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-218">The devices being deleted.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-219">Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f470b-219">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-220">Die Geräte, die gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-220">The devices being deleted.</span></span>
            </param>
        <param name="forceRemove">
            <span data-ttu-id="f470b-221">Erzwingt, dass das Objekt, ohne nach einer Übereinstimmung ETag entfernt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f470b-221">Forces the device object to be removed without regard for an ETag match.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-222">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-222">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-223">Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.</span><span class="sxs-lookup"><span data-stu-id="f470b-223">Deletes a list of previously registered devices from the system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwin As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-224">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-224">Device Id</span></span></param>
        <param name="newTwin"><span data-ttu-id="f470b-225">Neues Ziel-Objekt zum Ersetzen durch</span><span class="sxs-lookup"><span data-stu-id="f470b-225">New Twin object to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-226">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-226">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="f470b-227">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-227">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-228">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-228">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwinJson As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-229">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-229">Device Id</span></span></param>
        <param name="newTwinJson"><span data-ttu-id="f470b-230">Neue und JSON-Code durch Ersetzen</span><span class="sxs-lookup"><span data-stu-id="f470b-230">New Twin json to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-231">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-231">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="f470b-232">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-232">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-233">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-233">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-234">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-234">Device Id</span></span></param>
        <param name="newTwin"><span data-ttu-id="f470b-235">Neues Ziel-Objekt zum Ersetzen durch</span><span class="sxs-lookup"><span data-stu-id="f470b-235">New Twin object to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-236">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-236">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-237">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-237">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-238">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-238">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-239">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-239">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-240">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-240">Device Id</span></span></param>
        <param name="newTwinJson"><span data-ttu-id="f470b-241">Neue und JSON-Code durch Ersetzen</span><span class="sxs-lookup"><span data-stu-id="f470b-241">New Twin json to replace with</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-242">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-242">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-243">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-243">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-244">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-244">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-245">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-245">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-246">Das Objekt mit aktualisierten Felder.</span><span class="sxs-lookup"><span data-stu-id="f470b-246">The Device object with updated fields.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-247">Aktualisieren Sie die änderbare Felder von der geräteregistrierung</span><span class="sxs-lookup"><span data-stu-id="f470b-247">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-248">Echo wieder am Geräteobjekt mit aktualisierten etags</span><span class="sxs-lookup"><span data-stu-id="f470b-248">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-249">Das Objekt mit aktualisierten Felder.</span><span class="sxs-lookup"><span data-stu-id="f470b-249">The Device object with updated fields.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="f470b-250">Erzwingt, dass das Objekt ohne Berücksichtigung nach einer Übereinstimmung ETag ersetzt werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-250">Forces the device object to be replaced without regard for an ETag match.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-251">Aktualisieren Sie die änderbare Felder von der geräteregistrierung</span><span class="sxs-lookup"><span data-stu-id="f470b-251">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-252">Echo wieder am Geräteobjekt mit aktualisierten etags</span><span class="sxs-lookup"><span data-stu-id="f470b-252">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-253">Das Objekt mit aktualisierten Felder.</span><span class="sxs-lookup"><span data-stu-id="f470b-253">The Device object with updated fields.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-254">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-254">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-255">Aktualisieren Sie die änderbare Felder von der geräteregistrierung</span><span class="sxs-lookup"><span data-stu-id="f470b-255">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-256">Echo wieder am Geräteobjekt mit aktualisierten etags</span><span class="sxs-lookup"><span data-stu-id="f470b-256">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            <span data-ttu-id="f470b-257">Das Objekt mit aktualisierten Felder.</span><span class="sxs-lookup"><span data-stu-id="f470b-257">The Device object with updated fields.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="f470b-258">Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-258">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-259">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-259">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-260">Aktualisieren Sie die änderbare Felder von der geräteregistrierung</span><span class="sxs-lookup"><span data-stu-id="f470b-260">Update the mutable fields of the device registration</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-261">Echo wieder am Geräteobjekt mit aktualisierten etags</span><span class="sxs-lookup"><span data-stu-id="f470b-261">echoes back the Device object with updated etags</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-262">Geräteobjekte aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-262">The Device objects to be updated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-263">Aktualisieren einer Liste von Geräten mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-263">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-264">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-264">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-265">Geräteobjekte aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-265">The Device objects to be updated.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="f470b-266">Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-266">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-267">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-267">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-268">Aktualisieren einer Liste von Geräten mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-268">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-269">Gibt ein BulkRegistryOperationResult-Objekt</span><span class="sxs-lookup"><span data-stu-id="f470b-269">returns a BulkRegistryOperationResult object</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-270">Geräteobjekte aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-270">The Device objects to be updated.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-271">Aktualisieren einer Liste von Geräten mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-271">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-272">Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</span><span class="sxs-lookup"><span data-stu-id="f470b-272">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            <span data-ttu-id="f470b-273">Geräteobjekte aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-273">The Device objects to be updated.</span></span>
            </param>
        <param name="forceUpdate">
            <span data-ttu-id="f470b-274">Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-274">Forces the device object to be replaced even if it was updated since it was retrieved last time.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f470b-275">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="f470b-275">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f470b-276">Aktualisieren einer Liste von Geräten mit dem system</span><span class="sxs-lookup"><span data-stu-id="f470b-276">Update a list of devices with the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-277">Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</span><span class="sxs-lookup"><span data-stu-id="f470b-277">returns a string array of error messages</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, twinPatch As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-278">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-278">Device Id</span></span></param>
        <param name="twinPatch"><span data-ttu-id="f470b-279">Und mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-279">Twin with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-280">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-280">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="f470b-281">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-281">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-282">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-282">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, jsonTwinPatch As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-283">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-283">Device Id</span></span></param>
        <param name="jsonTwinPatch"><span data-ttu-id="f470b-284">Zwei Json mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-284">Twin json with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-285">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-285">Twin's etag</span></span></param>
        <summary>
            <span data-ttu-id="f470b-286">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-286">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-287">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-287">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-288">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-288">Device Id</span></span></param>
        <param name="twinPatch"><span data-ttu-id="f470b-289">Und mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-289">Twin with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-290">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-290">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-291">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-291">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-292">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-292">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-293">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-293">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="f470b-294">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="f470b-294">Device Id</span></span></param>
        <param name="jsonTwinPatch"><span data-ttu-id="f470b-295">Zwei Json mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-295">Twin json with updated fields</span></span></param>
        <param name="etag"><span data-ttu-id="f470b-296">Ziel des etag</span><span class="sxs-lookup"><span data-stu-id="f470b-296">Twin's etag</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-297">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-297">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-298">Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span><span class="sxs-lookup"><span data-stu-id="f470b-298">Updates the mutable fields of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></span></span></summary>
        <returns><span data-ttu-id="f470b-299">Aktualisierte und Instanz</span><span class="sxs-lookup"><span data-stu-id="f470b-299">Updated Twin instance</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async twins" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="f470b-300">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-300">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <summary>
            <span data-ttu-id="f470b-301">Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="f470b-301">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-302">Ergebnis des Massenvorgangs update</span><span class="sxs-lookup"><span data-stu-id="f470b-302">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin), forceUpdate As Boolean) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="f470b-303">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-303">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="forceUpdate"><span data-ttu-id="f470b-304">Erzwingt, dass die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekt aktualisiert werden, auch wenn er geändert hat, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-304">Forces the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> object to be updated even if it has changed since it was retrieved last time.</span></span></param>
        <summary>
            <span data-ttu-id="f470b-305">Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="f470b-305">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-306">Ergebnis des Massenvorgangs update</span><span class="sxs-lookup"><span data-stu-id="f470b-306">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="f470b-307">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-307">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-308">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-308">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-309">Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="f470b-309">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-310">Ergebnis des Massenvorgangs update</span><span class="sxs-lookup"><span data-stu-id="f470b-310">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins"><span data-ttu-id="f470b-311">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</span><span class="sxs-lookup"><span data-stu-id="f470b-311">List of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s with updated fields</span></span></param>
        <param name="forceUpdate"><span data-ttu-id="f470b-312">Erzwingt, dass die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekt aktualisiert werden, auch wenn er geändert hat, seit es zuletzt abgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="f470b-312">Forces the <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> object to be updated even if it has changed since it was retrieved last time.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="f470b-313">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="f470b-313">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="f470b-314">Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.</span><span class="sxs-lookup"><span data-stu-id="f470b-314">Update the mutable fields for a list of <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s previously created within the system</span></span>
            </summary>
        <returns><span data-ttu-id="f470b-315">Ergebnis des Massenvorgangs update</span><span class="sxs-lookup"><span data-stu-id="f470b-315">Result of the bulk update operation</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>