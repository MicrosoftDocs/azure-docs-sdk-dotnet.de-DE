<Type Name="ServiceClient" FullName="Microsoft.Azure.Devices.ServiceClient">
  <TypeSignature Language="C#" Value="public abstract class ServiceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ServiceClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.ServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ServiceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ServiceClient = class&#xA;    interface IDisposable" />
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
            <span data-ttu-id="9dd03-101">Enthält Methoden, die Dienste verwenden können, um Nachrichten an Geräte senden</span><span class="sxs-lookup"><span data-stu-id="9dd03-101">Contains methods that services can use to send messages to devices</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="serviceClient.CloseAsync " />
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
            <span data-ttu-id="9dd03-102">Schließen Sie die ServiceClient-Instanz</span><span class="sxs-lookup"><span data-stu-id="9dd03-102">Close the ServiceClient instance</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As ServiceClient" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.ServiceClient" Usage="Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ServiceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="9dd03-103">Verbindungszeichenfolge für die iothub</span><span class="sxs-lookup"><span data-stu-id="9dd03-103">Connection string for the iothub</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-104">Erstellen Sie aus der angegebenen Verbindungszeichenfolge ServiceClient</span><span class="sxs-lookup"><span data-stu-id="9dd03-104">Create ServiceClient from the specified connection string</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString (string connectionString, Microsoft.Azure.Devices.TransportType transportType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.ServiceClient CreateFromConnectionString(string connectionString, valuetype Microsoft.Azure.Devices.TransportType transportType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString(System.String,Microsoft.Azure.Devices.TransportType)" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string * Microsoft.Azure.Devices.TransportType -&gt; Microsoft.Azure.Devices.ServiceClient" Usage="Microsoft.Azure.Devices.ServiceClient.CreateFromConnectionString (connectionString, transportType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.ServiceClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="transportType" Type="Microsoft.Azure.Devices.TransportType" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="9dd03-105">Verbindungszeichenfolge für die iothub</span><span class="sxs-lookup"><span data-stu-id="9dd03-105">Connection string for the iothub</span></span></param>
        <param name="transportType"><span data-ttu-id="9dd03-106">Gibt an, ob Amqp oder Amqp über einen Websocket-Transport verwendet wird</span><span class="sxs-lookup"><span data-stu-id="9dd03-106">Specifies whether Amqp or Amqp over Websocket transport is used</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-107">Erstellen Sie aus der angegebenen Verbindungszeichenfolge mit der angegebenen Transporttyp ServiceClient</span><span class="sxs-lookup"><span data-stu-id="9dd03-107">Create ServiceClient from the specified connection string using specified Transport Type</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="serviceClient.Dispose " />
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="serviceClient.Dispose disposing" />
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
          <span data-ttu-id="9dd03-108"><c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</span><span class="sxs-lookup"><span data-stu-id="9dd03-108"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-109">Nicht verwaltete und optional verwaltete Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="9dd03-109">Releases unmanaged and - optionally - managed resources.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFeedbackReceiver">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt; GetFeedbackReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.FeedbackReceiver`1&lt;class Microsoft.Azure.Devices.FeedbackBatch&gt; GetFeedbackReceiver() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetFeedbackReceiver" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetFeedbackReceiver () As FeedbackReceiver(Of FeedbackBatch)" />
      <MemberSignature Language="F#" Value="abstract member GetFeedbackReceiver : unit -&gt; Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt;" Usage="serviceClient.GetFeedbackReceiver " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.FeedbackReceiver&lt;Microsoft.Azure.Devices.FeedbackBatch&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dd03-110">Abrufen der FeedbackReceiver</span><span class="sxs-lookup"><span data-stu-id="9dd03-110">Get the FeedbackReceiver</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-111">Eine Instanz von der FeedbackReceiver</span><span class="sxs-lookup"><span data-stu-id="9dd03-111">An instance of the FeedbackReceiver</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFileNotificationReceiver">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt; GetFileNotificationReceiver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.FileNotificationReceiver`1&lt;class Microsoft.Azure.Devices.FileNotification&gt; GetFileNotificationReceiver() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetFileNotificationReceiver" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetFileNotificationReceiver () As FileNotificationReceiver(Of FileNotification)" />
      <MemberSignature Language="F#" Value="abstract member GetFileNotificationReceiver : unit -&gt; Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt;" Usage="serviceClient.GetFileNotificationReceiver " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.FileNotificationReceiver&lt;Microsoft.Azure.Devices.FileNotification&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dd03-112">Abrufen der FeedbackReceiver</span><span class="sxs-lookup"><span data-stu-id="9dd03-112">Get the FeedbackReceiver</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-113">Eine Instanz von der FeedbackReceiver</span><span class="sxs-lookup"><span data-stu-id="9dd03-113">An instance of the FeedbackReceiver</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetServiceStatisticsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetServiceStatisticsAsync () As Task(Of ServiceStatistics)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatisticsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;" Usage="serviceClient.GetServiceStatisticsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9dd03-114">Ruft Dienst-Statistiken für den Iot Hub ab.</span><span class="sxs-lookup"><span data-stu-id="9dd03-114">Gets service statistics for the Iot Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-115">ServiceStatistics zurück, das aktuelle Service Statistiken enthält</span><span class="sxs-lookup"><span data-stu-id="9dd03-115">returns ServiceStatistics object containing current service statistics</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.ServiceStatistics&gt; GetServiceStatisticsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.GetServiceStatisticsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatisticsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;" Usage="serviceClient.GetServiceStatisticsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.ServiceStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            <span data-ttu-id="9dd03-116">Das Token, wodurch die der Vorgang abgebrochen werden.</span><span class="sxs-lookup"><span data-stu-id="9dd03-116">The token which allows the the operation to be cancelled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9dd03-117">Ruft Dienst-Statistiken für den Iot Hub ab.</span><span class="sxs-lookup"><span data-stu-id="9dd03-117">Gets service statistics for the Iot Hub.</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-118">ServiceStatistics zurück, das aktuelle Service Statistiken enthält</span><span class="sxs-lookup"><span data-stu-id="9dd03-118">returns ServiceStatistics object containing current service statistics</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync (string deviceId, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync(string deviceId, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.InvokeDeviceMethodAsync(System.String,Microsoft.Azure.Devices.CloudToDeviceMethod)" />
      <MemberSignature Language="F#" Value="abstract member InvokeDeviceMethodAsync : string * Microsoft.Azure.Devices.CloudToDeviceMethod -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;" Usage="serviceClient.InvokeDeviceMethodAsync (deviceId, cloudToDeviceMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="9dd03-119">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="9dd03-119">Device Id</span></span></param>
        <param name="cloudToDeviceMethod"><span data-ttu-id="9dd03-120">Gerät Methodenparameter (Pass-Through an Gerät)</span><span class="sxs-lookup"><span data-stu-id="9dd03-120">Device method parameters (passthrough to device)</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-121">Interaktiv Ruft eine Methode auf Gerät</span><span class="sxs-lookup"><span data-stu-id="9dd03-121">Interactively invokes a method on device</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-122">Methodenergebnis</span><span class="sxs-lookup"><span data-stu-id="9dd03-122">Method result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDeviceMethodAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync (string deviceId, Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt; InvokeDeviceMethodAsync(string deviceId, class Microsoft.Azure.Devices.CloudToDeviceMethod cloudToDeviceMethod, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.InvokeDeviceMethodAsync(System.String,Microsoft.Azure.Devices.CloudToDeviceMethod,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeDeviceMethodAsync : string * Microsoft.Azure.Devices.CloudToDeviceMethod * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;" Usage="serviceClient.InvokeDeviceMethodAsync (deviceId, cloudToDeviceMethod, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.CloudToDeviceMethodResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cloudToDeviceMethod" Type="Microsoft.Azure.Devices.CloudToDeviceMethod" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="9dd03-123">Geräte-ID</span><span class="sxs-lookup"><span data-stu-id="9dd03-123">Device Id</span></span></param>
        <param name="cloudToDeviceMethod"><span data-ttu-id="9dd03-124">Gerät Methodenparameter (Pass-Through an Gerät)</span><span class="sxs-lookup"><span data-stu-id="9dd03-124">Device method parameters (passthrough to device)</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="9dd03-125">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="9dd03-125">Cancellation Token</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-126">Interaktiv Ruft eine Methode auf Gerät</span><span class="sxs-lookup"><span data-stu-id="9dd03-126">Interactively invokes a method on device</span></span>
            </summary>
        <returns><span data-ttu-id="9dd03-127">Methodenergebnis</span><span class="sxs-lookup"><span data-stu-id="9dd03-127">Method result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="serviceClient.OpenAsync " />
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
            <span data-ttu-id="9dd03-128">Öffnen Sie die ServiceClient-Instanz</span><span class="sxs-lookup"><span data-stu-id="9dd03-128">Open the ServiceClient instance</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeMessageQueueAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.PurgeMessageQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function PurgeMessageQueueAsync (deviceId As String) As Task(Of PurgeMessageQueueResult)" />
      <MemberSignature Language="F#" Value="abstract member PurgeMessageQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;" Usage="serviceClient.PurgeMessageQueueAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId"></param>
        <summary>
            <span data-ttu-id="9dd03-129">Entfernt alle Nachrichten aus der Warteschlange des Geräts an.</span><span class="sxs-lookup"><span data-stu-id="9dd03-129">Removes all messages from a device's queue.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeMessageQueueAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.PurgeMessageQueueResult&gt; PurgeMessageQueueAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.PurgeMessageQueueAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeMessageQueueAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;" Usage="serviceClient.PurgeMessageQueueAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.PurgeMessageQueueResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="9dd03-130">Entfernt alle Nachrichten aus der Warteschlange des Geräts an.</span><span class="sxs-lookup"><span data-stu-id="9dd03-130">Removes all messages from a device's queue.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SendAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task SendAsync (string deviceId, Microsoft.Azure.Devices.Message message, Nullable&lt;TimeSpan&gt; timeout = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SendAsync(string deviceId, class Microsoft.Azure.Devices.Message message, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.ServiceClient.SendAsync(System.String,Microsoft.Azure.Devices.Message,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="F#" Value="abstract member SendAsync : string * Microsoft.Azure.Devices.Message * Nullable&lt;TimeSpan&gt; -&gt; System.Threading.Tasks.Task" Usage="serviceClient.SendAsync (deviceId, message, timeout)" />
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
        <Parameter Name="message" Type="Microsoft.Azure.Devices.Message" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="deviceId"><span data-ttu-id="9dd03-131">Die Geräte-ID für das Zielgerät</span><span class="sxs-lookup"><span data-stu-id="9dd03-131">The device identifier for the target device</span></span></param>
        <param name="message"><span data-ttu-id="9dd03-132">Die Nachricht, die die Benachrichtigung enthält.</span><span class="sxs-lookup"><span data-stu-id="9dd03-132">The message containing the notification</span></span></param>
        <param name="timeout"><span data-ttu-id="9dd03-133">Timeout für den Vorgang überschreiben.</span><span class="sxs-lookup"><span data-stu-id="9dd03-133">The operation timeout override.</span></span> <span data-ttu-id="9dd03-134">Wenn dies nicht der OperationTimeout-Standard verwendet wird</span><span class="sxs-lookup"><span data-stu-id="9dd03-134">If not used uses OperationTimeout default</span></span></param>
        <summary>
            <span data-ttu-id="9dd03-135">Eine unidirektionale Benachrichtigung an das angegebene Gerät senden</span><span class="sxs-lookup"><span data-stu-id="9dd03-135">Send a one-way notification to the specified device</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>