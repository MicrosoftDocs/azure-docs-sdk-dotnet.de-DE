<Type Name="FabricClient+TestManagementClient" FullName="System.Fabric.FabricClient+TestManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.TestManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/TestManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.TestManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.TestManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.TestManagementClient = class" />
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
      <para><span data-ttu-id="c58b3-101">Stellt Methoden zum Ausstellen und Test-Befehle zu steuern.</span><span class="sxs-lookup"><span data-stu-id="c58b3-101">Provides methods for issuing and controlling test commands.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-102">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</span><span class="sxs-lookup"><span data-stu-id="c58b3-102">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="c58b3-103">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-103">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="c58b3-104">Siehe Hinweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-104">See Remarks.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-105">Bricht einen Testbefehl ab.</span><span class="sxs-lookup"><span data-stu-id="c58b3-105">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-106">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-106">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-107">Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-107">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="c58b3-108">Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-108">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-109">Angeben von Force als "true" sollte mit Vorsicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-109">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="c58b3-110">Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.</span><span class="sxs-lookup"><span data-stu-id="c58b3-110">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="c58b3-111">Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-111">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="c58b3-112">Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-112">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="c58b3-113">Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.</span><span class="sxs-lookup"><span data-stu-id="c58b3-113">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="c58b3-114">Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-114">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            </para>
          <para>
            <span data-ttu-id="c58b3-115">Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.</span><span class="sxs-lookup"><span data-stu-id="c58b3-115">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-116">CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-116">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-117">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-117">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-118">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</span><span class="sxs-lookup"><span data-stu-id="c58b3-118">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="c58b3-119">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-119">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="c58b3-120">Siehe Hinweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-120">See Remarks.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-121">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-121">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-122">Bricht einen Testbefehl ab.</span><span class="sxs-lookup"><span data-stu-id="c58b3-122">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-123">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-123">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-124">Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-124">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="c58b3-125">Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-125">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-126">Angeben von Force als "true" sollte mit Vorsicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-126">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="c58b3-127">Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.</span><span class="sxs-lookup"><span data-stu-id="c58b3-127">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="c58b3-128">Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-128">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="c58b3-129">Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-129">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="c58b3-130">Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.</span><span class="sxs-lookup"><span data-stu-id="c58b3-130">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="c58b3-131">Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-131">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="c58b3-132">Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.</span><span class="sxs-lookup"><span data-stu-id="c58b3-132">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-133">CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-133">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-134">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-134">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function CancelTestCommandAsync (operationId As Guid, force As Boolean, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-135">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</span><span class="sxs-lookup"><span data-stu-id="c58b3-135">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="c58b3-136">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-136">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="c58b3-137">Siehe Hinweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-137">See Remarks.</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-138">Das Timeout für den API-Aufruf verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-138">The timeout to use for the API call.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-139">Bricht einen Testbefehl ab.</span><span class="sxs-lookup"><span data-stu-id="c58b3-139">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-140">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-140">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-141">Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-141">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="c58b3-142">Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-142">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-143">Angeben von Force als "true" sollte mit Vorsicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-143">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="c58b3-144">Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.</span><span class="sxs-lookup"><span data-stu-id="c58b3-144">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="c58b3-145">Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-145">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="c58b3-146">Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-146">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="c58b3-147">Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.</span><span class="sxs-lookup"><span data-stu-id="c58b3-147">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="c58b3-148">Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-148">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="c58b3-149">Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.</span><span class="sxs-lookup"><span data-stu-id="c58b3-149">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-150">CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-150">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-151">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-151">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelTestCommandAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelTestCommandAsync (Guid operationId, bool force, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelTestCommandAsync(valuetype System.Guid operationId, bool force, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CancelTestCommandAsync(System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelTestCommandAsync : Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CancelTestCommandAsync (operationId, force, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="force" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-152">Gibt an, die OperationId des testbefehls "auf" Abbrechen ".</span><span class="sxs-lookup"><span data-stu-id="c58b3-152">Indicates the operationId of the test command to cancel.</span></span></param>
        <param name="force"><span data-ttu-id="c58b3-153">Gibt an, ob geändert, um ordnungsgemäß Rollback und Bereinigen von internen Systemstatus durch den Testbefehl ausführen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-153">Indicates whether to gracefully rollback and clean up internal system state modified by executing the test command.</span></span>  <span data-ttu-id="c58b3-154">Siehe Hinweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-154">See Remarks.</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-155">Das Timeout für den API-Aufruf verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-155">The timeout to use for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-156">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-156">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-157">Bricht einen Testbefehl ab.</span><span class="sxs-lookup"><span data-stu-id="c58b3-157">Cancels a test command.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-158">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-158">A Task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-159">Wenn "Force" "false" ist, werden klicken Sie dann der Befehl angegebene Test ordnungsgemäß beendet und bereinigt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-159">If force is false, then the specified test command will be gracefully stopped and cleaned up.</span></span>  <span data-ttu-id="c58b3-160">Wenn Force auf "true" festgelegt ist, wird der Befehl abgebrochen werden, und möglicherweise ein interner Status beibehalten werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-160">If force is true, the command will be aborted, and some internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-161">Angeben von Force als "true" sollte mit Vorsicht verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-161">Specifying force as true should be used with care.</span></span>  <span data-ttu-id="c58b3-162">Aufruf CancelTestCommandAsync() mit Force auf "true" ist nicht zulässig, bis zum gleichen Befehl "Test" mit auf "false" First "Force" festgelegt CancelTestCommandAsync() aufgerufen wurde, oder der Testbefehl bereits eine TestCommandProgressState von TestCommandProgressState.RollingBack.</span><span class="sxs-lookup"><span data-stu-id="c58b3-162">Calling CancelTestCommandAsync() with force set to true is not allowed until CancelTestCommandAsync() has been called on the same test command with force set to false first, or unless the test command already has a TestCommandProgressState of TestCommandProgressState.RollingBack.</span></span>
            <span data-ttu-id="c58b3-163">Erläuterung: TestCommandProgressState.RollingBack bedeutet, dass das System wird/Bereinigen von internen Systemstatus, die durch Ausführen des Befehls verursacht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-163">Clarification: TestCommandProgressState.RollingBack means that the system will/is cleaning up internal system state caused by executing the command.</span></span>  <span data-ttu-id="c58b3-164">Daten wird nicht wiederhergestellt, wenn der Testbefehl wurde auf die Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-164">It will not restore data if the test command was to cause data loss.</span></span>  <span data-ttu-id="c58b3-165">Z. B. Wenn Sie StartPartitionDataLossAsync() dann CancelTestCommandAsync() aufrufen bereinigt das System nur interne Zustand von Ausführen des Befehls.</span><span class="sxs-lookup"><span data-stu-id="c58b3-165">For example, if you call StartPartitionDataLossAsync() then call CancelTestCommandAsync() the system will only clean up internal state from running the command.</span></span>  
            <span data-ttu-id="c58b3-166">Die Zielpartition-Daten wird nicht wiederhergestellt, wenn der Befehl weit genug fortgeschritten, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-166">It will not restore the target partition's data, if the command progressed far enough to cause data loss.</span></span>
            
            
            
            </para>
          <para>
            <span data-ttu-id="c58b3-167">Wichtiger Hinweis: Wenn diese API, mit dem Force aufgerufen wird == "true", der interne Zustand verbleibt hinter.</span><span class="sxs-lookup"><span data-stu-id="c58b3-167">Important note:  if this API is invoked with force==true, internal state may be left behind.</span></span>  <span data-ttu-id="c58b3-168">CleanTestStateAsync() sollte aufgerufen werden, um Status zu entfernen, die hinter verlassen wurde möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-168">CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-169">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-169">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c58b3-170">Bereinigt alle Teststatus im Cluster.</span><span class="sxs-lookup"><span data-stu-id="c58b3-170">Cleans up all the test state in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-171">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-171">Task</span></span></returns>
        <remarks>
            <span data-ttu-id="c58b3-172">Bereinigt alle Testzustand in den Cluster, der für die Fehlertoleranz Vorgänge festgelegt wurde; wie stopnode-Aufruf steht sollten InvokeDataLoss, RestartPartition und InvokeQuorumLoss diese API aufgerufen, wenn nicht mehr aktiv ist oder wenn der Testtreiber nicht verarbeiten oder ein Vorgang abgebrochen wird, während in-Flight aus, um sicherzustellen, dass der Cluster wieder in den Zustand "normal" ist einer dieser Vorgänge ein Fehler auf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-172">Cleans up all the test state in the cluster which has been set for fault operations; like StopNode, InvokeDataLoss, RestartPartition and InvokeQuorumLoss This API should be called if any of these operations fail or if the test driver process dies or an operation is canceled while in flight to ensure that the cluster is back into the normal state.</span></span> <span data-ttu-id="c58b3-173">Normalerweise alle Fehler Vorgänge Bereinigen von ihren Status am Ende der Ausführung der API so CleanTestState muss nur aufgerufen werden, wenn die API-Vorgang unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-173">Normally all the fault operations clean up their state at the end of the execution of the API so CleanTestState only needs to be called if the API operation is interrupted.</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-174">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-174">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="CleanTestStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CleanTestStateAsync (TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CleanTestStateAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.CleanTestStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function CleanTestStateAsync (operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.CleanTestStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.CleanTestStateAsync (operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="c58b3-175">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-175">The overall timeout for the operation.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-176">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-176">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-177">Bereinigt alle Teststatus im Cluster.</span><span class="sxs-lookup"><span data-stu-id="c58b3-177">Cleans up all the test state in the cluster.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-178">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-178">Task</span></span></returns>
        <remarks>
            <span data-ttu-id="c58b3-179">Bereinigt alle der Testzustand in den Cluster, der für Vorgänge der Fehlertoleranz, InvokeDataLoss, RestartPartition und InvokeQuorumLoss diese API festgelegt wurde aufgerufen werden, falls diese Vorgänge nicht oder wenn der Test-Treiber Prozess Dies oder einen Vorgang abgebrochen wird zwar Flight, um sicherzustellen, dass der Cluster wieder in den Zustand "normal" befindet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-179">Cleans up all the test state in the cluster which has been set for fault operations, InvokeDataLoss, RestartPartition and InvokeQuorumLoss This API should be called if any of these operations fail or if the test driver process dies or an operation is canceled while in flight to ensure that the cluster is back into the normal state.</span></span> <span data-ttu-id="c58b3-180">Normalerweise alle Fehler Vorgänge Bereinigen von ihren Status am Ende der Ausführung der API so CleanTestState muss nur aufgerufen werden, wenn die API-Vorgang unterbrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-180">Normally all the fault operations clean up their state at the end of the execution of the API so CleanTestState only needs to be called if the API operation is interrupted .</span></span>
            </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-181">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-181">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (filter As ChaosReportFilter) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="c58b3-182">Filter für die <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s, im Bericht eingeschlossen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-182">Filter for the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s to be included in the report.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-183">Ruft ab den Bericht über Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-183">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-184">Bericht der Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-184">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-185">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-185">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-186">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-186">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="c58b3-187">FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</span><span class="sxs-lookup"><span data-stu-id="c58b3-187">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChaosReportAsync (continuationToken As String) As Task(Of ChaosReport)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync continuationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="c58b3-188">Fortsetzungstoken für die Liste der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-188">Continuation token for the list of <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-189">Ruft ab den Bericht über Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-189">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-190">Bericht der Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-190">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-191">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-191">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-192">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-192">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="c58b3-193">FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</span><span class="sxs-lookup"><span data-stu-id="c58b3-193">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(class System.Fabric.Chaos.DataStructures.ChaosReportFilter filter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.Fabric.Chaos.DataStructures.ChaosReportFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : System.Fabric.Chaos.DataStructures.ChaosReportFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (filter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.Fabric.Chaos.DataStructures.ChaosReportFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filter"><span data-ttu-id="c58b3-194">Filter für die <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s im einzuschließenden der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-194">Filter for the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s to be included in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-195">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-195">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-196">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c58b3-196">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-197">Ruft ab den Bericht über Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-197">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-198">Bericht der Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-198">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-199">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-199">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-200">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-200">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-201">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-201">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="c58b3-202">FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</span><span class="sxs-lookup"><span data-stu-id="c58b3-202">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetChaosReportAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync (string continuationToken, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Chaos.DataStructures.ChaosReport&gt; GetChaosReportAsync(string continuationToken, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetChaosReportAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetChaosReportAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;" Usage="testManagementClient.GetChaosReportAsync (continuationToken, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Chaos.DataStructures.ChaosReport&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken"><span data-ttu-id="c58b3-203">Fortsetzungstoken für die Liste der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in der <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-203">Continuation token for the list of <see cref="T:System.Fabric.Chaos.DataStructures.ChaosEvent" />s in the <see cref="T:System.Fabric.Chaos.DataStructures.ChaosReport" />.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-204">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-204">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-205">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c58b3-205">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-206">Ruft ab den Bericht über Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-206">Retrieves the report of Chaos runs.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-207">Bericht der Chaos ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-207">Report of Chaos runs.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-208">Hierbei handelt es sich um Service Fabric-Ausnahmen und die folgenden Fehlercodes sollte überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-208">These are Service Fabric exceptions and the following error codes should be inspected.</span></span>
            <span data-ttu-id="c58b3-209">FabricErrorCode.NotReady – Wenn diese API aufgerufen wird, bevor Sie starten Chaos.</span><span class="sxs-lookup"><span data-stu-id="c58b3-209">FabricErrorCode.NotReady - if this API is called before starting Chaos.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeTransitionProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeTransitionProgress&gt; GetNodeTransitionProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetNodeTransitionProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeTransitionProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;" Usage="testManagementClient.GetNodeTransitionProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeTransitionProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-210">Der OperationId übergeben, wenn der Testbefehl mit StartNodeTransitionAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-210">The operationId passed in when the test command was started using StartNodeTransitionAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-211">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-211">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-212">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-212">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-213">Ruft den Status eines Befehls mit StartNodeTransitionAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-213">Gets the progress of a command started using StartNodeTransitionAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-214">Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-214">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks><span data-ttu-id="c58b3-215">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-215">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-216">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-216">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-217">Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-217">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-218">Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-218">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-219">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-219">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-220">Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-220">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-221">PartitionDataLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-221">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-222">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-222">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-223">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-223">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-224">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-224">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-225">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-225">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-226">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-226">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-227">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-227">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-228">Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-228">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-229">Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-229">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-230">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-230">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-231">Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-231">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-232">PartitionDataLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-232">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-233">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-233">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-234">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-234">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-235">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-235">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-236">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-236">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionDataLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionDataLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-237">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-237">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-238">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-238">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-239">Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-239">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-240">Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-240">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-241">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-241">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-242">Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-242">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-243">PartitionDataLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-243">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-244">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-244">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-245">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-245">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-246">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-246">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-247">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-247">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionDataLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionDataLossProgress&gt; GetPartitionDataLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionDataLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionDataLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;" Usage="testManagementClient.GetPartitionDataLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionDataLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-248">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionDataLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-248">The operationId passed in when the test command was starting using StartPartitionDataLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-249">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-249">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-250">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-250">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-251">Ruft den Status eines Test-Befehls mit StartPartitionDataLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-251">Gets the progress of a test command started using StartPartitionDataLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-252">Ein PartitionDataLossProgress-Objekt, das mit TestCommandProgressState und PartitionDataLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-252">A PartitionDataLossProgress object, containing TestCommandProgressState and PartitionDataLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-253">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-253">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-254">Wenn der zurückgegebene PartitionDataLossProgress.State == Faulted, PartitionDataLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-254">If the returned PartitionDataLossProgress.State == Faulted, examine PartitionDataLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-255">PartitionDataLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-255">PartitionDataLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-256">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-256">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-257">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-257">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-258">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-258">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-259">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-259">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-260">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-260">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-261">Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-261">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-262">Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-262">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-263">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-263">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="c58b3-264">Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-264">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-265">PartitionQuorumLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-265">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-266">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-266">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-267">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-267">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-268">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-268">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-269">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-269">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="c58b3-270">FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-270">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-271">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-271">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-272">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-272">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-273">Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-273">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-274">Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-274">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-275">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-275">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="c58b3-276">Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-276">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-277">PartitionQuorumLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-277">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-278">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-278">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-279">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-279">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-280">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-280">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-281">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-281">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="c58b3-282">FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-282">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionQuorumLossProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionQuorumLossProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-283">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-283">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-284">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-284">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-285">Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-285">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-286">Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-286">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-287">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-287">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="c58b3-288">Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-288">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-289">PartitionQuorumLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-289">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-290">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-290">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-291">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-291">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-292">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-292">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-293">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-293">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="c58b3-294">FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-294">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionQuorumLossProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionQuorumLossProgress&gt; GetPartitionQuorumLossProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionQuorumLossProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionQuorumLossProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;" Usage="testManagementClient.GetPartitionQuorumLossProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionQuorumLossProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-295">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionQuorumLossAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-295">The operationId passed in when the test command was starting using StartPartitionQuorumLossAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-296">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-296">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-297">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-297">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-298">Ruft den Status eines Test-Befehls mit StartPartitionQuorumLossAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-298">Gets the progress of a test command started using StartPartitionQuorumLossAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-299">Ein PartitionQuorumLossProgress-Objekt, das mit TestCommandProgressState und PartitionQuorumLossResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-299">A PartitionQuorumLossProgress object, containing TestCommandProgressState and PartitionQuorumLossResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-300">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-300">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para>
            <span data-ttu-id="c58b3-301">Wenn der zurückgegebene PartitionQuorumLossProgress.State == Faulted, PartitionQuorumLossProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-301">If the returned PartitionQuorumLossProgress.State == Faulted, examine PartitionQuorumLossProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-302">PartitionQuorumLossProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-302">PartitionQuorumLossProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-303">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-303">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-304">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-304">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-305">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-305">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
                - <span data-ttu-id="c58b3-306">FabricInvalidForStatelessServicesException - dieser Vorgang ist ungültig für zustandslose Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-306">FabricInvalidForStatelessServicesException - this operation is not valid for stateless services.</span></span>
                - <span data-ttu-id="c58b3-307">FabricOnlyValidForStatefulPersistentServicesException - dieser Vorgang ist ungültig für zustandsbehaftete in-Memory-Dienste.</span><span class="sxs-lookup"><span data-stu-id="c58b3-307">FabricOnlyValidForStatefulPersistentServicesException - this operation is not valid for stateful in-memory services.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync operationId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-308">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-308">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-309">Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-309">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-310">Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-310">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-311">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-311">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-312">Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-312">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-313">PartitionRestartProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-313">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-314">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-314">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-315">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-315">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-316">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-316">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-317">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-317">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-318">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-318">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-319">Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-319">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-320">Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-320">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-321">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-321">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-322">Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-322">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-323">PartitionRestartProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-323">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-324">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-324">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-325">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-325">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-326">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-326">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionRestartProgressAsync (operationId As Guid, timeout As TimeSpan) As Task(Of PartitionRestartProgress)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-327">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-327">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-328">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-328">Timeout.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-329">Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-329">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-330">Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-330">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-331">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-331">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-332">Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-332">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-333">PartitionRestartProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-333">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-334">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-334">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-335">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-335">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-336">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-336">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionRestartProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync (Guid operationId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PartitionRestartProgress&gt; GetPartitionRestartProgressAsync(valuetype System.Guid operationId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetPartitionRestartProgressAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionRestartProgressAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;" Usage="testManagementClient.GetPartitionRestartProgressAsync (operationId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PartitionRestartProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"><span data-ttu-id="c58b3-337">Der OperationId übergeben, wenn Sie der Testbefehl mit StartPartitionRestartAsync() gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-337">The operationId passed in when the test command was starting using StartPartitionRestartAsync().</span></span></param>
        <param name="timeout"><span data-ttu-id="c58b3-338">Timeout</span><span class="sxs-lookup"><span data-stu-id="c58b3-338">Timeout.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-339">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-339">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-340">Ruft den Status eines Test-Befehls mit StartPartitionRestartAsync() gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-340">Gets the progress of a test command started using StartPartitionRestartAsync().</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-341">Ein PartitionRestartProgress-Objekt, das mit TestCommandProgressState und PartitionRestartResult.</span><span class="sxs-lookup"><span data-stu-id="c58b3-341">A PartitionRestartProgress object, containing TestCommandProgressState and PartitionRestartResult.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="c58b3-342">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-342">The FaultAnalysisService must be enabled to use this API.</span></span></para>
          <para><span data-ttu-id="c58b3-343">Wenn der zurückgegebene PartitionRestartProgress.State == Faulted, PartitionRestartProgress.Result.Exception, um zu bestimmen, warum untersuchen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-343">If the returned PartitionRestartProgress.State == Faulted, examine PartitionRestartProgress.Result.Exception to determine why.</span></span>
            <span data-ttu-id="c58b3-344">PartitionRestartProgress.Result.Exception Werte:</span><span class="sxs-lookup"><span data-stu-id="c58b3-344">PartitionRestartProgress.Result.Exception values:</span></span>
              - <span data-ttu-id="c58b3-345">ArgumentException - Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-345">ArgumentException - the input was invalid.</span></span>
              - <span data-ttu-id="c58b3-346">FabricException mit einer ErrorCode-Eigenschaft der:</span><span class="sxs-lookup"><span data-stu-id="c58b3-346">FabricException, with an ErrorCode property of:</span></span>
                - <span data-ttu-id="c58b3-347">PartitionNotFound - die angegebene Partition, wurde nicht gefunden oder ist keine Partition, die den angegebenen Dienst gehört.</span><span class="sxs-lookup"><span data-stu-id="c58b3-347">PartitionNotFound - the specified partition was not found, or is not a partition that belongs to the specified service.</span></span>       
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="c58b3-348">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-348">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-349">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-349">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-350">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-350">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-351">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-351">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTestCommandStatusListAsync (operationTimeout As TimeSpan) As Task(Of TestCommandStatusList)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync operationTimeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="c58b3-352">Ein Timeout für die API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-352">A timeout for the API call.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-353">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-353">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-354">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-354">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-355">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-355">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"><span data-ttu-id="c58b3-356">Ein Timeout für die API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-356">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-357">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-357">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-358">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-358">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-359">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-359">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-360">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-360">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter"><span data-ttu-id="c58b3-361">Dieser Parameter kann verwendet werden, um nach TestCommandState zu filtern</span><span class="sxs-lookup"><span data-stu-id="c58b3-361">This parameter can be used to filter by TestCommandState</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-362">Ein Timeout für die API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-362">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-363">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-363">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-364">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-364">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-365">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-365">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-366">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-366">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="typeFilter"><span data-ttu-id="c58b3-367">Dieser Parameter kann verwendet werden, um nach TestCommandType zu filtern</span><span class="sxs-lookup"><span data-stu-id="c58b3-367">This parameter can be used to filter by TestCommandType</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-368">Ein Timeout für die API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-368">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-369">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-369">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-370">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-370">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-371">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-371">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-372">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-372">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestCommandStatusListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync (System.Fabric.Query.TestCommandStateFilter stateFilter, System.Fabric.Query.TestCommandTypeFilter typeFilter, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.TestCommandStatusList&gt; GetTestCommandStatusListAsync(valuetype System.Fabric.Query.TestCommandStateFilter stateFilter, valuetype System.Fabric.Query.TestCommandTypeFilter typeFilter, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetTestCommandStatusListAsync : System.Fabric.Query.TestCommandStateFilter * System.Fabric.Query.TestCommandTypeFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;" Usage="testManagementClient.GetTestCommandStatusListAsync (stateFilter, typeFilter, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.TestCommandStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="stateFilter" Type="System.Fabric.Query.TestCommandStateFilter" />
        <Parameter Name="typeFilter" Type="System.Fabric.Query.TestCommandTypeFilter" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="stateFilter"><span data-ttu-id="c58b3-373">Dieser Parameter kann verwendet werden, um nach TestCommandState zu filtern</span><span class="sxs-lookup"><span data-stu-id="c58b3-373">This parameter can be used to filter by TestCommandState</span></span></param>
        <param name="typeFilter"><span data-ttu-id="c58b3-374">Dieser Parameter kann verwendet werden, um nach TestCommandType zu filtern</span><span class="sxs-lookup"><span data-stu-id="c58b3-374">This parameter can be used to filter by TestCommandType</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-375">Ein Timeout für die API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-375">A timeout for the API call.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-376">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-376">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-377">Ruft den Status des Test-Befehle.</span><span class="sxs-lookup"><span data-stu-id="c58b3-377">Gets the status of test commands.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-378">Eine TestCommandStatusList, also eine IList von TestCommandStatus-Objekte</span><span class="sxs-lookup"><span data-stu-id="c58b3-378">A TestCommandStatusList, which is an IList of TestCommandStatus objects</span></span></returns>
        <remarks><span data-ttu-id="c58b3-379">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-379">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-380">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss</span><span class="sxs-lookup"><span data-stu-id="c58b3-380">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-381">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-381">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-382">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-382">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-383">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-383">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-384">InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-384">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-385">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-385">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-386">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-386">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-387">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-387">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-388">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-388">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-389">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-389">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-390">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-390">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-391">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-391">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-392">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-392">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-393">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-393">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-394">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-394">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-395">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-395">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-396">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-396">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-397">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-397">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-398">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-398">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-399">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-399">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-400">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-400">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-401">InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-401">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-402">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-402">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-403">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-403">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-404">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-404">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-405">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-405">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-406">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-406">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-407">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-407">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-408">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-408">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-409">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-409">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-410">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-410">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-411">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-411">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-412">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-412">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-413">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-413">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-414">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-414">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-415">Das gesamttimeout für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c58b3-415">The overall timeout for the operation</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-416">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-416">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-417">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-417">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-418">InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-418">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-419">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-419">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-420">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-420">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-421">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-421">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-422">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-422">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-423">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-423">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-424">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-424">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-425">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-425">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-426">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-426">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-427">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-427">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-428">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-428">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-429">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-429">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeDataLossResult&gt; InvokeDataLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeDataLossAsync(System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeDataLossAsync : System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;" Usage="testManagementClient.InvokeDataLossAsync (partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionDataLossAsync instead.  StartPartitionDataLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeDataLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-430">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-430">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-431">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-431">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-432">Das gesamttimeout für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c58b3-432">The overall timeout for the operation</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-433">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-433">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-434">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-434">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-435">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-435">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-436">InvokeDataLossResult die Informationen zur Partition, die enthält wurde von Datenverlust ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-436">InvokeDataLossResult which gives information about the Partition that was selected for data loss.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-437">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-437">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-438">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-438">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-439">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-439">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-440">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-440">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-441">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-441">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-442">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-442">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-443">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-443">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-444">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-444">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-445">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-445">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-446">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-446">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-447">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-447">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-448">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-448">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-449">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-449">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-450">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-450">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <summary><span data-ttu-id="c58b3-451">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-451">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-452">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="c58b3-452">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-453">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-453">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-454">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-454">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-455">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-455">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-456">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-456">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-457">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-457">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-458">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-458">Calling this API with a system service as the target is not advised.</span></span>                 
            </para>
          <para>
            <span data-ttu-id="c58b3-459">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-459">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-460">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-460">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-461">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-461">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-462">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-462">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-463">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-463">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-464">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-464">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-465">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-465">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-466">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-466">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-467">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-467">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-468">Das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-468">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-469">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-469">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-470">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="c58b3-470">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-471">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-471">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-472">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-472">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-473">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-473">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-474">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-474">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-475">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-475">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-476">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-476">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-477">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-477">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-478">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-478">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-479">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-479">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-480">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-480">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-481">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-481">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-482">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-482">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-483">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-483">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-484">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-484">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-485">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-485">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-486">Allgemeines Timeout für den gesamten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-486">Overall timeout for the entire operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-487">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-487">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-488">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="c58b3-488">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-489">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-489">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-490">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-490">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-491">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-491">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-492">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-492">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-493">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-493">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-494">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-494">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-495">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-495">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-496">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-496">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-497">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-497">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-498">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-498">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-499">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-499">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-500">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-500">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="InvokeQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.InvokeQuorumLossResult&gt; InvokeQuorumLossAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.InvokeQuorumLossAsync(System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeQuorumLossAsync : System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;" Usage="testManagementClient.InvokeQuorumLossAsync (partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionQuorumLossAsync instead.  StartPartitionQuorumLossAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.InvokeQuorumLossResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector"><span data-ttu-id="c58b3-501">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-501">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode"><span data-ttu-id="c58b3-502">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-502">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumlossDuration"><span data-ttu-id="c58b3-503">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-503">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-504">Allgemeines Timeout für den gesamten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-504">Overall timeout for the entire operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-505">Das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-505">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-506">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-506">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-507">InvokeQuorumLossResult<see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span><span class="sxs-lookup"><span data-stu-id="c58b3-507">InvokeQuorumLossResult <see cref="T:System.Fabric.Result.InvokeQuorumLossResult" /></span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-508">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-508">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-509">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-509">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-510">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-510">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-511">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-511">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-512">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-512">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-513">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-513">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-514">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-514">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-515">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-515">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-516">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-516">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-517">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-517">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-518">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-518">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-519">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-519">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-520"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-520"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-521">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-521">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-522">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-522">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-523">Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-523">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-524">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-524">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-525">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-525">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-526">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-526">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-527">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-527">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-528">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-528">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-529">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-529">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-530">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-530">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-531">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-531">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-532">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-532">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-533"><see cref="T:System.Fabric.PartitionSelector" />die angibt, dass der Partitions, die muss neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-533"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-534">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-534">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-535">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-535">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-536">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-536">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-537">Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-537">RestartPartitionResult which gives information about the actual selected partition</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-538">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-538">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-539">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-539">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-540">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-540">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-541">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-541">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-542">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-542">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-543">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-543">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-544">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-544">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-545">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-545">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-546">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-546">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-547"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-547"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-548">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-548">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-549">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-549">The overall timeout for the operation.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-550">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-550">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-551">Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-551">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-552">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-552">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-553">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-553">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-554">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-554">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-555">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-555">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-556">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-556">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-557">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-557">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-558">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-558">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-559">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-559">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-560">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-560">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="RestartPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync (System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Result.RestartPartitionResult&gt; RestartPartitionAsync(class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.RestartPartitionAsync(System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartPartitionAsync : System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;" Usage="testManagementClient.RestartPartitionAsync (partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use StartPartitionRestartAsync instead.  StartPartitionRestartAsync requires the FaultAnalysisService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Result.RestartPartitionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-561"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-561"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-562">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-562">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-563">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-563">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-564">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-564">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-565">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-565">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-566">Die Informationen zu den tatsächlichen gewährt RestartPartitionResult Partition ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-566">RestartPartitionResult which gives information about the actual selected partition.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-567">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-567">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-568">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-568">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-569">Wichtiger Hinweis: Diese API nicht während der Ausführung abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c58b3-569">Important note:  this API should not be aborted while running.</span></span>  <span data-ttu-id="c58b3-570">Diese API wird abgebrochen, während der Ausführung Zustand bleiben möglicherweise.</span><span class="sxs-lookup"><span data-stu-id="c58b3-570">Aborting this API while it is running may leave state behind.</span></span>  
            <span data-ttu-id="c58b3-571">Wenn diese API während der Ausführung abgebrochen wird, sollte die CleanTestStateAsync() um Zustand zu entfernen, die hinter verlassen wurde möglicherweise aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-571">If this API is aborted while running, CleanTestStateAsync() should be invoked to remove state that may have been left behind.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-572">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-572">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-573">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-573">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-574">Wenn die API, für eine Partition aufgerufen wird, die zu eines zustandslosen Diensts mit gehören <see cref="T:System.Fabric.RestartPartitionMode" /> OnlyActiveSecondaries festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c58b3-574">If the API is called for a partition belonging to a stateless service with <see cref="T:System.Fabric.RestartPartitionMode" /> set to OnlyActiveSecondaries.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-575">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-575">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync chaosParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
      </Parameters>
      <Docs>
        <param name="chaosParameters">
          <span data-ttu-id="c58b3-576"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" />enthält verschiedene Parameter zum Steuern von Chaos; z. B. Zeit ausgeführt wird, maximale Anzahl von gleichzeitigen Fautls usw.</span><span class="sxs-lookup"><span data-stu-id="c58b3-576"><see cref="T:System.Fabric.Chaos.DataStructures.ChaosParameters" /> contains various parameters for controlling Chaos; e.g., time to run, maximum number of concurrent fautls, etc.</span></span> </param>
        <summary>
            <span data-ttu-id="c58b3-577">Diese API wird mit den angegebenen Parameterwerten Chaos gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-577">This API will start Chaos with the supplied parameter values.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-578">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-578">A task.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-579">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-579">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-580">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-580">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException"><span data-ttu-id="c58b3-581">Diese Ausnahme wird ausgelöst, wenn die StartChaos-API aufgerufen wird, während Chaos bereits im Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-581">This exception is thrown when StartChaos API is invoked while Chaos is already running in the cluster.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartChaosAsync (System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartChaosAsync(class System.Fabric.Chaos.DataStructures.ChaosParameters chaosParameters, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartChaosAsync(System.Fabric.Chaos.DataStructures.ChaosParameters,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartChaosAsync : System.Fabric.Chaos.DataStructures.ChaosParameters * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartChaosAsync (chaosParameters, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="chaosParameters" Type="System.Fabric.Chaos.DataStructures.ChaosParameters" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="chaosParameters"> <span data-ttu-id="c58b3-582">Enthält verschiedene Parameter zum Steuern von Chaos; z. B. Zeit ausgeführt wird, maximale Anzahl von gleichzeitigen Fehlern usw.</span><span class="sxs-lookup"><span data-stu-id="c58b3-582">Contains various parameters for controlling Chaos; e.g., time to run, maximum number of concurrent faults, etc.</span></span></param>
        <param name="operationTimeout"> <span data-ttu-id="c58b3-583">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-583">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"> <span data-ttu-id="c58b3-584">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c58b3-584">Cancellation token.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-585">Diese API wird mit den angegebenen Parameterwerten Chaos gestartet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-585">This API will start Chaos with the supplied parameter values.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-586">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-586">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-587">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-587">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-588">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-588">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-589">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-589">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricChaosAlreadyRunningException"><span data-ttu-id="c58b3-590">Diese Ausnahme wird ausgelöst, wenn die StartChaos-API aufgerufen wird, während Chaos bereits im Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-590">This exception is thrown when StartChaos API is invoked while Chaos is already running in the cluster.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartNodeTransitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartNodeTransitionAsync (System.Fabric.Description.NodeTransitionDescription description, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartNodeTransitionAsync(class System.Fabric.Description.NodeTransitionDescription description, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartNodeTransitionAsync(System.Fabric.Description.NodeTransitionDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function StartNodeTransitionAsync (description As NodeTransitionDescription, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.StartNodeTransitionAsync : System.Fabric.Description.NodeTransitionDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartNodeTransitionAsync (description, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.NodeTransitionDescription" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="c58b3-591">Ein Objekt der Art des Knotens Übergangs auszuführenden beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-591">An object which describes what type of node transition to perform.</span></span>  <span data-ttu-id="c58b3-592">Der Übergang kann zum Starten oder Beenden eines Knotens sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-592">The transition can be to start or stop a node.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-593">Das Timeout für diesen API-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="c58b3-593">The timeout for this API call.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-594">Das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="c58b3-594">The cancellationToken</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-595">Startet oder beendet einen Clusterknoten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-595">Starts or stops a cluster node.</span></span>  <span data-ttu-id="c58b3-596">Ein Clusterknoten ist ein Prozess, nicht die Betriebssysteminstanz selbst.</span><span class="sxs-lookup"><span data-stu-id="c58b3-596">A cluster node is a process, not the OS instance itself.</span></span>  <span data-ttu-id="c58b3-597">Um einen Knoten zu starten, übergeben Sie ein Objekt des Typs NodeStartDescription in der Description-Parameter.</span><span class="sxs-lookup"><span data-stu-id="c58b3-597">To start a node, pass in an object of type NodeStartDescription into the description parameter.</span></span>  <span data-ttu-id="c58b3-598">Um einen Knoten zu beenden, übergeben Sie ein Objekt vom Typ NodeStopDescription.</span><span class="sxs-lookup"><span data-stu-id="c58b3-598">To stop a node, pass in an object of type NodeStopDescription.</span></span>  <span data-ttu-id="c58b3-599">Nachdem diese API zurückgegeben hat, rufen Sie GetNodeTransitionProgressAsync(), um den Fortschritt des Vorgangs abzurufen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-599">After this API returns, call GetNodeTransitionProgressAsync() to get progress on the operation.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-600">Eine Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-600">A task</span></span></returns>
        <remarks><span data-ttu-id="c58b3-601">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-601">The FaultAnalysisService must be enabled to use this API.</span></span></remarks>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-602">Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft wird der Grund dafür angegeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-602">The <see cref="P:System.Fabric.FabricException.ErrorCode" /> property will indicate the reason.</span></span>        
              <span data-ttu-id="c58b3-603">Wenn ErrorCode InstanceIdMismatch ist, entspricht der bereitgestellten NodeInstance nicht die Instanz des Knotens, der angehalten wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-603">If the errorCode is InstanceIdMismatch, the nodeInstance provided does not match the instance of the node that was stopped.</span></span>      
            </exception>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-604">Beim Vorgang ist ein Timeout aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-604">The operation timed out.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-605">Ein Argument mit einem Wert von Null übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="c58b3-605">An argument with a value of null was passed in.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-606">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-606">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API.</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-607">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust verursacht werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-607">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-608">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-608">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-609">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-609">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-610">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-610">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-611">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-611">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-612">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-612">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" />.</span></span>
            <span data-ttu-id="c58b3-613">PartialDataLoss - nur ein Quorum der Replikate werden entfernt und OnDataLoss wird ausgelöst, für die Partition tatsächlich Datenverlust hängt jedoch Vorhandensein von in-Flight-Replikation.</span><span class="sxs-lookup"><span data-stu-id="c58b3-613">PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-614">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-614">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-615">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-615">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-616">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-616">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-617">Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-617">Note:  Once this API has been called, it cannot be reversed.</span></span> <span data-ttu-id="c58b3-618">CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-618">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>
            <span data-ttu-id="c58b3-619">Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-619">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-620">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-620">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-621">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-621">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-622">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-622">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-623">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-623">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-624">Hierbei handelt es sich um die Fabric-Fehler.</span><span class="sxs-lookup"><span data-stu-id="c58b3-624">These are the fabric failures.</span></span>
            <span data-ttu-id="c58b3-625">FabricErrorCode.PartitionNotFound - Wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-625">FabricErrorCode.PartitionNotFound - If the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-626">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-626">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-627">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-627">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-628">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-628">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-629">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-629">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-630">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-630">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-631">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-631">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-632">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-632">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-633">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-633">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of inflight replication.</span></span>
            <span data-ttu-id="c58b3-634">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-634">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-635">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-635">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-636">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-636">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-637">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-637">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-638">Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-638">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="c58b3-639">CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-639">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>  
            <span data-ttu-id="c58b3-640">Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-640">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-641">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-641">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-642">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-642">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-643">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-643">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-644">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-644">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-645">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-645">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-646">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-646">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-647">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-647">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-648">Das gesamttimeout für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c58b3-648">The overall timeout for the operation</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-649">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-649">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-650">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-650">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-651">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-651">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-652">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-652">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-653">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-653">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-654">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-654">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-655">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-655">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-656">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-656">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-657">Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-657">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="c58b3-658">CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-658">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>  
            <span data-ttu-id="c58b3-659">Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-659">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-660">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-660">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-661">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-661">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-662">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-662">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-663">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-663">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionDataLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.DataLossMode dataLossMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionDataLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.DataLossMode dataLossMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionDataLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.DataLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionDataLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.DataLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionDataLossAsync (operationId, partitionSelector, dataLossMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="dataLossMode" Type="System.Fabric.DataLossMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-664">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-664">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-665">Die <see cref="T:System.Fabric.PartitionSelector" /> an, welche Partition Datenverlust für ausgelöst werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-665">The <see cref="T:System.Fabric.PartitionSelector" /> to specify which partition data loss needs to be induced for.</span></span></param>
        <param name="dataLossMode"><span data-ttu-id="c58b3-666">Gibt an, die <see cref="T:System.Fabric.DataLossMode" /> z. B. die Optionen für ratenbasierte Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-666">Specifies the <see cref="T:System.Fabric.DataLossMode" /> i.e. the options for inducing data loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-667">Das gesamttimeout für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="c58b3-667">The overall timeout for the operation</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-668">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-668">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-669">Diese API wird Datenverlust für die angegebene Partition auslösen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-669">This API will induce data loss for the specified partition.</span></span> <span data-ttu-id="c58b3-670">Löst einen Aufruf der API OnDataLoss der Partition.</span><span class="sxs-lookup"><span data-stu-id="c58b3-670">It will trigger a call to the OnDataLoss API of the partition.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-671">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-671">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-672">Tatsächliche Datenverlust hängt von der angegebenen <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - nur ein Quorum der Replikate werden entfernt und tatsächlichen Datenverlust hängt Vorhandensein von in-Flight-Replikation jedoch OnDataLoss für die Partition ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-672">Actual data loss will depend on the specified <see cref="T:System.Fabric.DataLossMode" /> PartialDataLoss - PartialDataLoss - Only a quorum of replicas are removed and OnDataLoss is triggered for the partition but actual data loss depends on presence of in-flight replication.</span></span>
            <span data-ttu-id="c58b3-673">Alle Replikate befinden sich FullDataLoss - entfernt daher alle Daten verloren und OnDataLoss ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-673">FullDataLoss - All replicas are removed hence all data is lost and OnDataLoss is triggered.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-674">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-674">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-675">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-675">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-676">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-676">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-677">Hinweis: Sobald diese API aufgerufen wurde, kann nicht rückgängig gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-677">Note:  Once this API has been called, it cannot be reversed.</span></span>  <span data-ttu-id="c58b3-678">CancelTestCommandAsync() aufrufen, wird nur die Ausführung beenden und bereinigen Sie internen Systemstatus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-678">Calling CancelTestCommandAsync() will only stop execution and clean up internal system state.</span></span>
            <span data-ttu-id="c58b3-679">Es werden Daten nicht wiederherstellen, wenn der Befehl weit genug fortgeschritten ist, zu Datenverlust führen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-679">It will not restore data if the command has progressed far enough to cause data loss.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-680">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-680">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-681">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-681">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"><span data-ttu-id="c58b3-682">Wenn die API für eine Partition, die zu eines zustandslosen Diensts gehören aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-682">If the API is called for a partition belonging to a stateless service.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-683">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-683">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-684">Ein vom Benutzer bereitgestellte-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="c58b3-684">A user-provided identifier.</span></span>  <span data-ttu-id="c58b3-685">Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-685">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-686">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-686">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-687">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-687">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-688">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-688">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <summary><span data-ttu-id="c58b3-689">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-689">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-690">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-690">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-691">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-691">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-692">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-692">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-693">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-693">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-694">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-694">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-695">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-695">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-696">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-696">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-697">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-697">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-698">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-698">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-699">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-699">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-700">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-700">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-701">Ein vom Benutzer bereitgestellte-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="c58b3-701">A user-provided identifier.</span></span>  <span data-ttu-id="c58b3-702">Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-702">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-703">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-703">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-704">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-704">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-705">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-705">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-706">Das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-706">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-707">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-707">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-708">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-708">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-709">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-709">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-710">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-710">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-711">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-711">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-712">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-712">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-713">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-713">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-714">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-714">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-715">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-715">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-716">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-716">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-717">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-717">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-718">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-718">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumLossMode, TimeSpan quorumLossDuration, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumLossMode, valuetype System.TimeSpan quorumLossDuration, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumLossMode, quorumLossDuration, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumLossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumLossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-719">Ein vom Benutzer bereitgestellte-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="c58b3-719">A user-provided identifier.</span></span>  <span data-ttu-id="c58b3-720">Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-720">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-721">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-721">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumLossMode"><span data-ttu-id="c58b3-722">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-722">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumLossDuration"><span data-ttu-id="c58b3-723">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-723">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-724">Allgemeines Timeout für den gesamten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-724">Overall timeout for the entire operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-725">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-725">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-726">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-726">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-727">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-727">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-728">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-728">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-729">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-729">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-730">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-730">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-731">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-731">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-732">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-732">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-733">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-733">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-734">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-734">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-735">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-735">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-736">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-736">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionQuorumLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionQuorumLossAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.QuorumLossMode quorumlossMode, TimeSpan quorumlossDuration, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionQuorumLossAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.QuorumLossMode quorumlossMode, valuetype System.TimeSpan quorumlossDuration, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionQuorumLossAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.QuorumLossMode,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionQuorumLossAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.QuorumLossMode * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionQuorumLossAsync (operationId, partitionSelector, quorumlossMode, quorumlossDuration, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="quorumlossMode" Type="System.Fabric.QuorumLossMode" />
        <Parameter Name="quorumlossDuration" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-737">Ein vom Benutzer bereitgestellte-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="c58b3-737">A user-provided identifier.</span></span>  <span data-ttu-id="c58b3-738">Dieser Bezeichner kann auch in die entsprechende "GetProgress"-API übergeben werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-738">This identifier can also be passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector"><span data-ttu-id="c58b3-739">Die Partition, die aufgerufen wird, das Clusterquorum verloren geht.</span><span class="sxs-lookup"><span data-stu-id="c58b3-739">Partition which the quorum loss will be invoked.</span></span> <see cref="T:System.Fabric.PartitionSelector" /></param>
        <param name="quorumlossMode"><span data-ttu-id="c58b3-740">PartialQuorumLoss oder FullQuorumLoss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-740">PartialQuorumLoss or FullQuorumLoss.</span></span></param>
        <param name="quorumlossDuration"><span data-ttu-id="c58b3-741">Zeitdauer für die Partition in quorumsverlust bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-741">Amount of time for which the partition will be kept in quorum loss.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-742">Allgemeines Timeout für den gesamten Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-742">Overall timeout for the entire operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-743">Das Abbruchtoken, das für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-743">The cancellation token for the operation.</span></span></param>
        <summary><span data-ttu-id="c58b3-744">Löst einen Quorumverlust für eine bestimmte zustandsbehaftete Dienstpartition aus.</span><span class="sxs-lookup"><span data-stu-id="c58b3-744">Induces quorum loss for a given stateful service partition.</span></span> </summary>
        <returns><span data-ttu-id="c58b3-745">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-745">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-746">FullQuorumLoss - alle Replikate für die Zielpartition wird wobei sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-746">FullQuorumLoss - All replicas for the target partition will be downed.</span></span>
            <span data-ttu-id="c58b3-747">PartialQuorumLoss - ein Quorum der Replikate für die Zielpartition wird wobei werden...</span><span class="sxs-lookup"><span data-stu-id="c58b3-747">PartialQuorumLoss - A quorum of replicas for the target partition will be downed..</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-748">QuorumLossMode gibt die Anzahl der Replikate, die fehlerhaft sein wird, um das Quorum verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-748">quorumLossMode indicates the number of replicas that will be faulted in order to cause quorum loss.</span></span> <span data-ttu-id="c58b3-749">Die Partition wird in quorumsverlust für QuorumLossDuration bleiben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-749">The partition will remain in quorum loss for quorumLossDuration.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-750">Diese API sollte nur mit einem zustandsbehafteten Dienst als Ziel aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-750">This API should only be called with a stateful service as the target.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-751">Aufrufe dieser API mit einem Systemdienst als Ziel wird davon abgeraten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-751">Calling this API with a system service as the target is not advised.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-752">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-752">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-753">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-753">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="c58b3-754">Asynchroner Vorgang abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-754">Async operation is canceled.</span></span></exception>
        <exception cref="T:System.InvalidOperationException"> <span data-ttu-id="c58b3-755">Angegebene Partition ist nicht Teil eines zustandsbehafteten Diensts beibehalten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-755">Partition specified is not a part of a stateful Persisted Service.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-756">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-756">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-757"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-757"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-758">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-758">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-759">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-759">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-760">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-760">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-761">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-761">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-762">Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-762">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="c58b3-763">Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-763">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="c58b3-764">Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-764">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="c58b3-765">Finden Sie unter GetPartitionRestartProgressAsync().</span><span class="sxs-lookup"><span data-stu-id="c58b3-765">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-766">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-766">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-767">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-767">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-768">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-768">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="c58b3-769">Die Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-769">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-770">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="c58b3-770">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-771">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-771">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-772"><see cref="T:System.Fabric.PartitionSelector" />die angibt, dass der Partitions, die muss neu gestartet werden</span><span class="sxs-lookup"><span data-stu-id="c58b3-772"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-773">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-773">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-774">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-774">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-775">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-775">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-776">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-776">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-777">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-777">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-778">Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-778">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="c58b3-779">Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-779">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="c58b3-780">Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-780">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="c58b3-781">Finden Sie unter GetPartitionRestartProgressAsync().</span><span class="sxs-lookup"><span data-stu-id="c58b3-781">See GetPartitionRestartProgressAsync().</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-782">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-782">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-783">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-783">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="c58b3-784">Die Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-784">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-785">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-785">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-786">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-786">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-787"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-787"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-788">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-788">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-789">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-789">The overall timeout for the operation.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-790">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-790">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-791">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-791">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-792">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-792">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-793">Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-793">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="c58b3-794">Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-794">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="c58b3-795">Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-795">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="c58b3-796">Finden Sie unter GetPartitionRestartProgressAsync().</span><span class="sxs-lookup"><span data-stu-id="c58b3-796">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-797">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-797">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-798">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-798">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-799">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-799">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="c58b3-800">Die Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-800">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-801">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-801">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StartPartitionRestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartPartitionRestartAsync (Guid operationId, System.Fabric.PartitionSelector partitionSelector, System.Fabric.RestartPartitionMode restartPartitionMode, TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StartPartitionRestartAsync(valuetype System.Guid operationId, class System.Fabric.PartitionSelector partitionSelector, valuetype System.Fabric.RestartPartitionMode restartPartitionMode, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StartPartitionRestartAsync(System.Guid,System.Fabric.PartitionSelector,System.Fabric.RestartPartitionMode,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StartPartitionRestartAsync : Guid * System.Fabric.PartitionSelector * System.Fabric.RestartPartitionMode * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StartPartitionRestartAsync (operationId, partitionSelector, restartPartitionMode, operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="partitionSelector" Type="System.Fabric.PartitionSelector" />
        <Parameter Name="restartPartitionMode" Type="System.Fabric.RestartPartitionMode" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationId"> <span data-ttu-id="c58b3-802">Eine GUID, die einen Aufruf dieser API bezeichnet; Dies wird in die entsprechende "GetProgress"-API übergeben.</span><span class="sxs-lookup"><span data-stu-id="c58b3-802">A GUID that identifies a call of this API; this is passed into the corresponding GetProgress API</span></span></param>
        <param name="partitionSelector">
          <span data-ttu-id="c58b3-803"><see cref="T:System.Fabric.PartitionSelector" />die gibt der Partitions, die neu gestartet werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-803"><see cref="T:System.Fabric.PartitionSelector" /> that specifies the partition which needs to be restarted.</span></span></param>
        <param name="restartPartitionMode"><span data-ttu-id="c58b3-804">Die <see cref="T:System.Fabric.RestartPartitionMode" /> die AllReplicasOrInstances sein kann oder OnlyActiveSecondaries basierend auf dem die Replikate neu gestartet werden, ausgewählt sind.</span><span class="sxs-lookup"><span data-stu-id="c58b3-804">The <see cref="T:System.Fabric.RestartPartitionMode" /> which can be AllReplicasOrInstances or OnlyActiveSecondaries based on which the replicas to be restarted are selected.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-805">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-805">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c58b3-806">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-806">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-807">Diese API startet einige oder alle Replikate einer Partition (es wird sichergestellt, dass sind alle Replikate gleichzeitig heruntergefahren wird) gleichzeitig je nach den <see cref="T:System.Fabric.RestartPartitionMode" />.</span><span class="sxs-lookup"><span data-stu-id="c58b3-807">This API will restart some or all the replicas of a partition at the same time (ensures all the replicas are down concurrently) depending on the <see cref="T:System.Fabric.RestartPartitionMode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-808">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-808">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-809">Diese API ist nützlich, um die Wiederherstellungszeit einer Partition nach einem Neustart vollständig oder teilweise zu testen und Failover zu testen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-809">This API is useful to test the recovery time of a partition after a full or partial restart and also to test failover.</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-810">Für zustandsbehaftete und zustandslose Dienste kann diese API aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-810">This API may be called on both stateful and stateless services.</span></span>  
            <span data-ttu-id="c58b3-811">Wenn der Aufruf auf eines zustandslosen Diensts handelt, muss die RestartPartitionMode RestartPartitionMode.AllReplicasOrInstances sein.</span><span class="sxs-lookup"><span data-stu-id="c58b3-811">If the call is on a stateless service, RestartPartitionMode must be RestartPartitionMode.AllReplicasOrInstances.</span></span>  <span data-ttu-id="c58b3-812">Andere Modi führt zu ArgumentException in das zurückgegebene Ergebnis-Objekt, wenn GetPartitionRestartProgressAsync() aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="c58b3-812">Other modes will result in ArgumentException inside the returned Result object when GetPartitionRestartProgressAsync() is called.</span></span>  <span data-ttu-id="c58b3-813">Finden Sie unter GetPartitionRestartProgressAsync().</span><span class="sxs-lookup"><span data-stu-id="c58b3-813">See GetPartitionRestartProgressAsync().</span></span>
            </para>
          <para>
            <span data-ttu-id="c58b3-814">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-814">The FaultAnalysisService must be enabled to use this API.</span></span>             
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-815">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-815">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-816">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-816">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="c58b3-817">Die Eingabe ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="c58b3-817">The input was invalid.</span></span></exception>
        <exception cref="T:System.Fabric.FabricException"><span data-ttu-id="c58b3-818">Dies sind die Fabric-Fehler FabricErrorCode.PartitionNotFound -, wenn die angegebene Partition ausgewählt, nicht vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="c58b3-818">These are the fabric failures FabricErrorCode.PartitionNotFound - if the specified partition selected does not exist</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function StopChaosAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : unit -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c58b3-819">Diese API wird Chaos beendet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-819">This API will stop Chaos.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-820">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-820">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-821">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-821">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StopChaosAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopChaosAsync (TimeSpan operationTimeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task StopChaosAsync(valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.StopChaosAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.StopChaosAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.StopChaosAsync (operationTimeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationTimeout"> <span data-ttu-id="c58b3-822">Das gesamttimeout für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-822">The overall timeout for the operation.</span></span></param>
        <param name="cancellationToken"> <span data-ttu-id="c58b3-823">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-823">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-824">Diese API wird Chaos beendet.</span><span class="sxs-lookup"><span data-stu-id="c58b3-824">This API will stop Chaos.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-825">Eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="c58b3-825">A task.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c58b3-826">Die FaultAnalysisService muss aktiviert sein, um diese API verwenden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-826">The FaultAnalysisService must be enabled to use this API.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-827">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-827">Action took more than its allocated time.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="c58b3-828">Der Name der Anwendung, deren Dienste überprüft werden müssen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-828">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-829">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-829">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-830">Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-830">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-831">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-831">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-832">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-832">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-833">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-833">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-834">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-834">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="c58b3-835">Der Name der Anwendung, deren Dienste überprüft werden müssen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-835">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-836">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-836">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-837">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-837">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-838">Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-838">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-839">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-839">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-840">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-840">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-841">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-841">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-842">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-842">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateApplicationAsync (Uri applicationName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateApplicationAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateApplicationAsync (applicationName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateApplicationAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateApplicationAsync (applicationName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName"><span data-ttu-id="c58b3-843">Der Name der Anwendung, deren Dienste überprüft werden müssen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-843">Name of the application whose services need to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-844">Max. Zeitraum, für die Dienste anderer Fehler stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-844">Max amount of time to wait for the services to stabilize else fail the operation.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-845">Die Zeitspanne auf den Vorgang andernfalls Fail Abschluss eines Vorgangs zu warten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-845">Amount of time to wait for an operation to complete else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-846">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-846">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-847">Diese API wird die Verfügbarkeit und Integrität aller Dienste in der angegebenen Anwendung überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-847">This API will validate the availability and health of all services in the specified application.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-848">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-848">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-849">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-849">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-850">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-850">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-851">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-851">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="c58b3-852">Der Name des Diensts, der überprüft werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-852">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-853">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-853">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-854">Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-854">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-855">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-855">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-856">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-856">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-857">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-857">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-858">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-858">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="c58b3-859">Der Name des Diensts, der überprüft werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-859">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-860">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-860">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-861">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-861">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-862">Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-862">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-863">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-863">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-864">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-864">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-865">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-865">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-866">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-866">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="ValidateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ValidateServiceAsync (Uri serviceName, TimeSpan maximumStabilizationTimeout, TimeSpan operationTimeout, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ValidateServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan maximumStabilizationTimeout, valuetype System.TimeSpan operationTimeout, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.TestManagementClient.ValidateServiceAsync(System.Uri,System.TimeSpan,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateServiceAsync (serviceName As Uri, maximumStabilizationTimeout As TimeSpan, operationTimeout As TimeSpan, token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ValidateServiceAsync : Uri * TimeSpan * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testManagementClient.ValidateServiceAsync (serviceName, maximumStabilizationTimeout, operationTimeout, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="maximumStabilizationTimeout" Type="System.TimeSpan" />
        <Parameter Name="operationTimeout" Type="System.TimeSpan" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName"><span data-ttu-id="c58b3-867">Der Name des Diensts, der überprüft werden muss.</span><span class="sxs-lookup"><span data-stu-id="c58b3-867">Name of the service that needs to be validated.</span></span></param>
        <param name="maximumStabilizationTimeout"><span data-ttu-id="c58b3-868">Max. Zeitraum, für den Dienst else Fail stabilisiert warten Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c58b3-868">Max amount of time to wait for the service to stabilize else fail the operation.</span></span></param>
        <param name="operationTimeout"><span data-ttu-id="c58b3-869">Die Zeitspanne auf den Vorgang andernfalls Fail Abschluss eines Vorgangs zu warten.</span><span class="sxs-lookup"><span data-stu-id="c58b3-869">Amount of time to wait for an operation to complete else fail the operation.</span></span></param>
        <param name="token"><span data-ttu-id="c58b3-870">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="c58b3-870">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="c58b3-871">Diese API wird die Verfügbarkeit und Integrität des angegebenen Diensts überprüfen.</span><span class="sxs-lookup"><span data-stu-id="c58b3-871">This API will validate the availability and health of the specified service.</span></span>
            </summary>
        <returns><span data-ttu-id="c58b3-872">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="c58b3-872">Task</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="c58b3-873">Aktion dauerte länger als der vorgesehenen Zeit.</span><span class="sxs-lookup"><span data-stu-id="c58b3-873">Action took more than its allocated time.</span></span></exception>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="c58b3-874">Eines der erforderlichen Argumente sind null.</span><span class="sxs-lookup"><span data-stu-id="c58b3-874">Any of the required arguments are null.</span></span></exception>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="c58b3-875">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c58b3-875">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>