<Type Name="FabricClient+RepairManagementClient" FullName="System.Fabric.FabricClient+RepairManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.RepairManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/RepairManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.RepairManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.RepairManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.RepairManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="de368-101">Stellt Methoden zum Verwalten von Tasks reparieren.</span><span class="sxs-lookup"><span data-stu-id="de368-101">Provides methods for managing repair tasks.</span></span></para>
      <para><span data-ttu-id="de368-102">Diese Klasse unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="de368-102">This class supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelRepairTaskAsync (repairTaskId As String, version As Long, requestAbort As Boolean) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-103">Die ID des Tasks "Reparieren" werden abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="de368-103">The ID of the repair task to be cancelled.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-104">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-104">The current version number of the repair task.</span></span> <span data-ttu-id="de368-105">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-105">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-106">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-106">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="requestAbort">
          <para>
            <span data-ttu-id="de368-107"><languageKeyword>"True"</languageKeyword> , wenn die Reparatur so bald wie möglich beendet werden soll, selbst wenn sie bereits begonnen wurde ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-107"><languageKeyword>True</languageKeyword> if the repair should be stopped as soon as possible even if it has already started executing.</span></span> <span data-ttu-id="de368-108"><languageKeyword>"False"</languageKeyword> , wenn die Reparatur abgebrochen werden sollte, nur dann, wenn die Ausführung noch nicht gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="de368-108"><languageKeyword>False</languageKeyword> if the repair should be cancelled only if execution has not yet started.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-109">Fordert den Abbruch des Tasks "angegebenen reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-109">Requests the cancellation of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-110">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-110">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CancelRepairTaskAsync (string repairTaskId, long version, bool requestAbort, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CancelRepairTaskAsync(string repairTaskId, int64 version, bool requestAbort, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CancelRepairTaskAsync(System.String,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelRepairTaskAsync : string * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CancelRepairTaskAsync (repairTaskId, version, requestAbort, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="requestAbort" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-111">Die ID des Tasks "Reparieren" werden abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="de368-111">The ID of the repair task to be cancelled.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-112">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-112">The current version number of the repair task.</span></span> <span data-ttu-id="de368-113">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-113">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-114">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-114">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="requestAbort">
          <para>
            <span data-ttu-id="de368-115"><languageKeyword>"True"</languageKeyword> , wenn die Reparatur so bald wie möglich beendet werden soll, selbst wenn sie bereits begonnen wurde ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-115"><languageKeyword>True</languageKeyword> if the repair should be stopped as soon as possible even if it has already started executing.</span></span> <span data-ttu-id="de368-116"><languageKeyword>"False"</languageKeyword> , wenn die Reparatur abgebrochen werden sollte, nur dann, wenn die Ausführung noch nicht gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="de368-116"><languageKeyword>False</languageKeyword> if the repair should be cancelled only if execution has not yet started.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-117">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-117">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-118">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-118">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-119">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-119">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-120">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-120">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-121">Fordert den Abbruch des Tasks "angegebenen reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-121">Requests the cancellation of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-122">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-122">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> <span data-ttu-id="de368-123">Die Beschreibung des Tasks "Reparieren" erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-123">The description of the repair task to be created.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-124">Erstellt einen neuen Reparaturtask an.</span><span class="sxs-lookup"><span data-stu-id="de368-124">Creates a new repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-125">Die Versionsnummer des Tasks neu erstellter reparieren.</span><span class="sxs-lookup"><span data-stu-id="de368-125">The version number of the newly-created repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; CreateRepairTaskAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; CreateRepairTaskAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.CreateRepairTaskAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateRepairTaskAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.CreateRepairTaskAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask">
          <para> <span data-ttu-id="de368-126">Die Beschreibung des Tasks "Reparieren" erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-126">The description of the repair task to be created.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-127">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine<see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-127">The maximum amount of time Service Fabric will allow this operation to continue before returning a<see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para> <span data-ttu-id="de368-128">Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-128">The optional cancellation token that the operation is observing.It can be used to send a notification that the operation should be canceled.</span></span>
            <span data-ttu-id="de368-129">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-129">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-130">Erstellt einen neuen Reparaturtask an.</span><span class="sxs-lookup"><span data-stu-id="de368-130">Creates a new repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-131">Die Versionsnummer des Tasks neu erstellter reparieren.</span><span class="sxs-lookup"><span data-stu-id="de368-131">The version number of the newly-created repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRepairTaskAsync (repairTaskId As String, version As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-132">Die ID des abgeschlossenen Reparaturtasks, der gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-132">The ID of the completed repair task to be deleted.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-133">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-133">The current version number of the repair task.</span></span> <span data-ttu-id="de368-134">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-134">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-135">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-135">If zero, then no version check is performed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-136">Löscht die angegebenen reparaturaufgabe an.</span><span class="sxs-lookup"><span data-stu-id="de368-136">Deletes the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-137">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="de368-137">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.DeleteRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="repairManagementClient.DeleteRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-138">Die ID des abgeschlossenen Reparaturtasks, der gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-138">The ID of the completed repair task to be deleted.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-139">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-139">The current version number of the repair task.</span></span> <span data-ttu-id="de368-140">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-140">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-141">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-141">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-142">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-142">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-143">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-143">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-144">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-144">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-145">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-145">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-146">Löscht die angegebenen reparaturaufgabe an.</span><span class="sxs-lookup"><span data-stu-id="de368-146">Deletes the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-147">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="de368-147">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ForceApproveRepairTaskAsync (repairTaskId As String, version As Long) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-148">Die ID des Tasks "Reparieren" genehmigt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-148">The ID of the repair task to be approved.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-149">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-149">The current version number of the repair task.</span></span> <span data-ttu-id="de368-150">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-150">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-151">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-151">If zero, then no version check is performed.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-152">Erzwingt die Genehmigung das angegebenen Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-152">Forces the approval of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-153">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-153">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceApproveRepairTaskAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; ForceApproveRepairTaskAsync (string repairTaskId, long version, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; ForceApproveRepairTaskAsync(string repairTaskId, int64 version, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.ForceApproveRepairTaskAsync(System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ForceApproveRepairTaskAsync : string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.ForceApproveRepairTaskAsync (repairTaskId, version, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-154">Die ID des Tasks "Reparieren" genehmigt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-154">The ID of the repair task to be approved.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-155">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-155">The current version number of the repair task.</span></span> <span data-ttu-id="de368-156">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-156">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-157">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-157">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-158">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-158">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-159">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-159">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-160">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-160">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-161">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-161">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-162">Erzwingt die Genehmigung das angegebenen Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-162">Forces the approval of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-163">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-163">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync () As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="de368-164">Ruft eine Liste aller reparieren Aufgaben ab.</span><span class="sxs-lookup"><span data-stu-id="de368-164">Gets a list of all repair tasks.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-165">Die Liste der Tasks für alle reparieren.</span><span class="sxs-lookup"><span data-stu-id="de368-165">The list of all repair tasks.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="de368-166">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-166">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-167">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-167">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-168">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-168">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-169">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-169">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-170">Ruft eine Liste aller reparieren Aufgaben ab.</span><span class="sxs-lookup"><span data-stu-id="de368-170">Gets a list of all repair tasks.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-171">Die Liste der Tasks für alle reparieren.</span><span class="sxs-lookup"><span data-stu-id="de368-171">The list of all repair tasks.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRepairTaskListAsync (taskIdFilter As String, stateFilter As RepairTaskStateFilter, executorFilter As String) As Task(Of RepairTaskList)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para><span data-ttu-id="de368-172">Das Reparaturtask-ID-Präfix, das abgeglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-172">The repair task ID prefix to be matched.</span></span>  <span data-ttu-id="de368-173">Der Task-ID wird kein Filter angewendet, wenn der Wert null ist,</span><span class="sxs-lookup"><span data-stu-id="de368-173">If null, no filter is applied to the task ID.</span></span></para>
        </param>
        <param name="stateFilter">
          <para><span data-ttu-id="de368-174">Eine bitweise Kombination der Filter-Statuswerte, die angeben, welche Aufgabe Zustände sollte in der Liste enthalten sein.</span><span class="sxs-lookup"><span data-stu-id="de368-174">A bitwise combination of state filter values that specify which task states should be included in the list.</span></span></para>
        </param>
        <param name="executorFilter">
          <para><span data-ttu-id="de368-175">Der Name der Executor für die Reparatur, deren beanspruchte Aufgaben in der Liste enthalten sein soll.</span><span class="sxs-lookup"><span data-stu-id="de368-175">The name of the repair executor whose claimed tasks should be included in the list.</span></span> <span data-ttu-id="de368-176">Bei null wird kein Filter auf den Namen der Executor angewendet.</span><span class="sxs-lookup"><span data-stu-id="de368-176">If null, no filter is applied to the executor name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-177">Ruft eine Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="de368-177">Gets a list of repair tasks matching all of the given filters.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-178">Die Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="de368-178">The list of repair tasks matching all of the given filters.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRepairTaskListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync (string taskIdFilter, System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Repair.RepairTaskList&gt; GetRepairTaskListAsync(string taskIdFilter, valuetype System.Fabric.Repair.RepairTaskStateFilter stateFilter, string executorFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.GetRepairTaskListAsync(System.String,System.Fabric.Repair.RepairTaskStateFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRepairTaskListAsync : string * System.Fabric.Repair.RepairTaskStateFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;" Usage="repairManagementClient.GetRepairTaskListAsync (taskIdFilter, stateFilter, executorFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Repair.RepairTaskList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskIdFilter" Type="System.String" />
        <Parameter Name="stateFilter" Type="System.Fabric.Repair.RepairTaskStateFilter" />
        <Parameter Name="executorFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskIdFilter">
          <para><span data-ttu-id="de368-179">Das Reparaturtask-ID-Präfix, das abgeglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-179">The repair task ID prefix to be matched.</span></span>  <span data-ttu-id="de368-180">Der Task-ID wird kein Filter angewendet, wenn der Wert null ist,</span><span class="sxs-lookup"><span data-stu-id="de368-180">If null, no filter is applied to the task ID.</span></span></para>
        </param>
        <param name="stateFilter">
          <para><span data-ttu-id="de368-181">Eine bitweise Kombination der Filter-Statuswerte, die angeben, welche Aufgabe Zustände sollte in der Liste enthalten sein.</span><span class="sxs-lookup"><span data-stu-id="de368-181">A bitwise combination of state filter values that specify which task states should be included in the list.</span></span></para>
        </param>
        <param name="executorFilter">
          <para><span data-ttu-id="de368-182">Der Name der Executor für die Reparatur, deren beanspruchte Aufgaben in der Liste enthalten sein soll.</span><span class="sxs-lookup"><span data-stu-id="de368-182">The name of the repair executor whose claimed tasks should be included in the list.</span></span> <span data-ttu-id="de368-183">Bei null wird kein Filter auf den Namen der Executor angewendet.</span><span class="sxs-lookup"><span data-stu-id="de368-183">If null, no filter is applied to the executor name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-184">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-184">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-185">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-185">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-186">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-186">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-187">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-187">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-188">Ruft eine Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="de368-188">Gets a list of repair tasks matching all of the given filters.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-189">Die Liste der Tasks reparieren, die alle angegebenen Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="de368-189">The list of repair tasks matching all of the given filters.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync repairTask" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
      </Parameters>
      <Docs>
        <param name="repairTask"><span data-ttu-id="de368-190">Die geänderte reparaturaufgabe.</span><span class="sxs-lookup"><span data-stu-id="de368-190">The modified repair task.</span></span></param>
        <summary>
            <span data-ttu-id="de368-191">Aktualisiert eine reparaturaufgabe.</span><span class="sxs-lookup"><span data-stu-id="de368-191">Updates a repair task.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="de368-192">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-192">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairExecutionStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairExecutionStateAsync (System.Fabric.Repair.RepairTask repairTask, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairExecutionStateAsync(class System.Fabric.Repair.RepairTask repairTask, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairExecutionStateAsync(System.Fabric.Repair.RepairTask,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairExecutionStateAsync : System.Fabric.Repair.RepairTask * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairExecutionStateAsync (repairTask, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTask" Type="System.Fabric.Repair.RepairTask" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTask"><span data-ttu-id="de368-193">Die geänderte reparaturaufgabe.</span><span class="sxs-lookup"><span data-stu-id="de368-193">The modified repair task.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="de368-194">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-194">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-195">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-195">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-196">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-196">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-197">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-197">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="de368-198">Aktualisiert eine reparaturaufgabe.</span><span class="sxs-lookup"><span data-stu-id="de368-198">Updates a repair task.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="de368-199">Die neue Versionsnummer des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-199">The new version number of the repair task.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRepairTaskHealthPolicyAsync (repairTaskId As String, version As Long, performPreparingHealthCheck As Nullable(Of Boolean), performRestoringHealthCheck As Nullable(Of Boolean)) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-200">Die ID des Tasks "Reparieren" für die ist die Integritätsrichtlinie aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="de368-200">The ID of the repair task for which the health policy is to be updated.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-201">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-201">The current version number of the repair task.</span></span> <span data-ttu-id="de368-202">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-202">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-203">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-203">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            <span data-ttu-id="de368-204">Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Vorbereiten des Tasks "Reparieren" ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-204">A nullable boolean indicating if health check is to be performed in the Preparing stage of the repair task.</span></span>
            <span data-ttu-id="de368-205">Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="de368-205">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="de368-206">Geben Sie andernfalls den gewünschten neuen Wert ein.</span><span class="sxs-lookup"><span data-stu-id="de368-206">Otherwise, specify the desired new value.</span></span> 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            <span data-ttu-id="de368-207">Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Restoring des Tasks "Reparieren" ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-207">A nullable boolean indicating if health check is to be performed in the Restoring stage of the repair task.</span></span>
            <span data-ttu-id="de368-208">Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="de368-208">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="de368-209">Geben Sie andernfalls den gewünschten neuen Wert ein.</span><span class="sxs-lookup"><span data-stu-id="de368-209">Otherwise, specify the desired new value.</span></span> 
            </para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-210">Aktualisiert die Richtlinie für Integritätsstatus des Tasks "angegebenen reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-210">Updates the health policy of the given repair task.</span></span></para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRepairTaskHealthPolicyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; UpdateRepairTaskHealthPolicyAsync (string repairTaskId, long version, Nullable&lt;bool&gt; performPreparingHealthCheck, Nullable&lt;bool&gt; performRestoringHealthCheck, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; UpdateRepairTaskHealthPolicyAsync(string repairTaskId, int64 version, valuetype System.Nullable`1&lt;bool&gt; performPreparingHealthCheck, valuetype System.Nullable`1&lt;bool&gt; performRestoringHealthCheck, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.RepairManagementClient.UpdateRepairTaskHealthPolicyAsync(System.String,System.Int64,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateRepairTaskHealthPolicyAsync : string * int64 * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="repairManagementClient.UpdateRepairTaskHealthPolicyAsync (repairTaskId, version, performPreparingHealthCheck, performRestoringHealthCheck, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="repairTaskId" Type="System.String" />
        <Parameter Name="version" Type="System.Int64" />
        <Parameter Name="performPreparingHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="performRestoringHealthCheck" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="repairTaskId">
          <para><span data-ttu-id="de368-211">Die ID des Tasks "Reparieren" für die ist die Integritätsrichtlinie aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="de368-211">The ID of the repair task for which the health policy is to be updated.</span></span></para>
        </param>
        <param name="version">
          <para><span data-ttu-id="de368-212">Die aktuelle Versionsnummer des Reparaturtasks.</span><span class="sxs-lookup"><span data-stu-id="de368-212">The current version number of the repair task.</span></span> <span data-ttu-id="de368-213">Wenn ungleich 0 (null) ist, wird die Anforderung nur erfolgreich, wenn dieser Wert den tatsächlichen aktuellen Wert des Tasks "Reparieren" übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="de368-213">If non-zero, then the request will only succeed if this value matches the actual current value of the repair task.</span></span> <span data-ttu-id="de368-214">Ist der Wert gleich null, wird keine Versionsüberprüfung ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="de368-214">If zero, then no version check is performed.</span></span></para>
        </param>
        <param name="performPreparingHealthCheck">
          <para>
            <span data-ttu-id="de368-215">Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Vorbereiten des Tasks "Reparieren" ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-215">A nullable boolean indicating if health check is to be performed in the Preparing stage of the repair task.</span></span>
            <span data-ttu-id="de368-216">Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="de368-216">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="de368-217">Geben Sie andernfalls den entsprechenden <c>Bool</c> Wert.</span><span class="sxs-lookup"><span data-stu-id="de368-217">Else, specify the appropriate <c>bool</c> value.</span></span> 
            </para>
        </param>
        <param name="performRestoringHealthCheck">
          <para>
            <span data-ttu-id="de368-218">Ein boolescher Wert NULL-Werte zulässt, der angibt, wenn der integritätsprüfung wird in der Phase Restoring des Tasks "Reparieren" ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="de368-218">A nullable boolean indicating if health check is to be performed in the Restoring stage of the repair task.</span></span>
            <span data-ttu-id="de368-219">Geben Sie <c>null</c> für diesen Parameter, wenn der vorhandene Wert nicht geändert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="de368-219">Specify <c>null</c> for this parameter if the existing value should not be altered.</span></span> <span data-ttu-id="de368-220">Geben Sie andernfalls den entsprechenden <c>Bool</c> Wert.</span><span class="sxs-lookup"><span data-stu-id="de368-220">Else, specify the appropriate <c>bool</c> value.</span></span> 
            </para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="de368-221">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="de368-221">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="de368-222">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="de368-222">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="de368-223">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="de368-223">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="de368-224">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="de368-224">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="de368-225">Aktualisiert die Richtlinie für Integritätsstatus des Tasks "angegebenen reparieren".</span><span class="sxs-lookup"><span data-stu-id="de368-225">Updates the health policy of the given repair task.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="de368-226">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="de368-226">A task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>