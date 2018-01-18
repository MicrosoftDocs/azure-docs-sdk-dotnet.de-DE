<Type Name="RepairTaskHealthCheckState" FullName="System.Fabric.Repair.RepairTaskHealthCheckState">
  <TypeSignature Language="C#" Value="public enum RepairTaskHealthCheckState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskHealthCheckState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskHealthCheckState" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskHealthCheckState" />
  <TypeSignature Language="F#" Value="type RepairTaskHealthCheckState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="2fb13-101">Gibt den Workflowstatus von einem reparaturaufgabe integritätsprüfung, gelangt die reparaturaufgabe Zustand vorbereiten "oder" Wiederherstellen ".</span><span class="sxs-lookup"><span data-stu-id="2fb13-101">Specifies the workflow state of a repair task's health check when the repair task enters either the Preparing or Restoring state.</span></span></para>
    </summary>
    <remarks><span data-ttu-id="2fb13-102">Separate integritätsprüfungen fertig sind, reparaturaufträgen gelangt das Vorbereiten und Status wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="2fb13-102">Separate health checks are done when a repair task enters the Preparing and Restoring states.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="InProgress">
      <MemberSignature Language="C#" Value="InProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState InProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.InProgress" />
      <MemberSignature Language="VB.NET" Value="InProgress" />
      <MemberSignature Language="F#" Value="InProgress = 1" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.InProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fb13-103">Gibt an, dass die integritätsprüfung ausgeführt wird</span><span class="sxs-lookup"><span data-stu-id="2fb13-103">Indicates that the health check is in progress</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NotStarted">
      <MemberSignature Language="C#" Value="NotStarted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState NotStarted = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.NotStarted" />
      <MemberSignature Language="VB.NET" Value="NotStarted" />
      <MemberSignature Language="F#" Value="NotStarted = 0" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.NotStarted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fb13-104">Gibt an, dass die integritätsprüfung noch nicht gestartet.</span><span class="sxs-lookup"><span data-stu-id="2fb13-104">Indicates that the health check hasn't started.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Skipped">
      <MemberSignature Language="C#" Value="Skipped" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState Skipped = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.Skipped" />
      <MemberSignature Language="VB.NET" Value="Skipped" />
      <MemberSignature Language="F#" Value="Skipped = 3" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.Skipped" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fb13-105">Gibt an, dass die integritätsprüfung ausgelassen wurde.</span><span class="sxs-lookup"><span data-stu-id="2fb13-105">Indicates that the health check was skipped.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="Succeeded" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState Succeeded = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Succeeded" />
      <MemberSignature Language="F#" Value="Succeeded = 2" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.Succeeded" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fb13-106">Gibt an, dass die integritätsprüfung erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="2fb13-106">Indicates that the health check succeeded.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TimedOut">
      <MemberSignature Language="C#" Value="TimedOut" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskHealthCheckState TimedOut = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskHealthCheckState.TimedOut" />
      <MemberSignature Language="VB.NET" Value="TimedOut" />
      <MemberSignature Language="F#" Value="TimedOut = 4" Usage="System.Fabric.Repair.RepairTaskHealthCheckState.TimedOut" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskHealthCheckState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2fb13-107">Gibt an, dass ein der integritätsprüfung durchgeführt werden Timeout.</span><span class="sxs-lookup"><span data-stu-id="2fb13-107">Indicates that the health check timed out.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>