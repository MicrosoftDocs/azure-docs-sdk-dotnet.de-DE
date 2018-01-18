<Type Name="TestCommandProgressState" FullName="System.Fabric.TestCommandProgressState">
  <TypeSignature Language="C#" Value="public enum TestCommandProgressState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TestCommandProgressState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.TestCommandProgressState" />
  <TypeSignature Language="VB.NET" Value="Public Enum TestCommandProgressState" />
  <TypeSignature Language="F#" Value="type TestCommandProgressState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="4e421-101">Diese Enumeration gibt den Status eines Test-Befehls.</span><span class="sxs-lookup"><span data-stu-id="4e421-101">This enum indicates the state of a test command.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancelled">
      <MemberSignature Language="C#" Value="Cancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Cancelled = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Cancelled" />
      <MemberSignature Language="VB.NET" Value="Cancelled" />
      <MemberSignature Language="F#" Value="Cancelled = 5" Usage="System.Fabric.TestCommandProgressState.Cancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-102">Der Testbefehl wurde vom Benutzer mit der CancelTestCommandAsync() abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="4e421-102">The test command was cancelled by the user using CancelTestCommandAsync()</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Completed = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 3" Usage="System.Fabric.TestCommandProgressState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-103">Der Testbefehl wurde erfolgreich abgeschlossen und ist nicht mehr ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="4e421-103">The test command has completed successfully and is no longer running.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Faulted">
      <MemberSignature Language="C#" Value="Faulted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Faulted = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Faulted" />
      <MemberSignature Language="VB.NET" Value="Faulted" />
      <MemberSignature Language="F#" Value="Faulted = 4" Usage="System.Fabric.TestCommandProgressState.Faulted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-104">Mit dem Testbefehl ist fehlgeschlagen und wird nicht mehr ausgeführt</span><span class="sxs-lookup"><span data-stu-id="4e421-104">The test command has failed and is no longer running</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ForceCancelled">
      <MemberSignature Language="C#" Value="ForceCancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState ForceCancelled = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.ForceCancelled" />
      <MemberSignature Language="VB.NET" Value="ForceCancelled" />
      <MemberSignature Language="F#" Value="ForceCancelled = 6" Usage="System.Fabric.TestCommandProgressState.ForceCancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-105">Der Testbefehl wurde vom Benutzer mit der CancelTestCommandAsync(), mit der Force-Parameter auf "true" festgelegt wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="4e421-105">The test command was cancelled by the user using CancelTestCommandAsync(), with the force parameter set to true</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.TestCommandProgressState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-106">Der Befehlsstatus Test ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="4e421-106">The test command state is invalid.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBack">
      <MemberSignature Language="C#" Value="RollingBack" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState RollingBack = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.RollingBack" />
      <MemberSignature Language="VB.NET" Value="RollingBack" />
      <MemberSignature Language="F#" Value="RollingBack = 2" Usage="System.Fabric.TestCommandProgressState.RollingBack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-107">Der Testbefehl einen Rollback internen Systemstatus, da es ist einen Schwerwiegender Fehler aufgetreten oder der vom Benutzer abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="4e421-107">The test command is rolling back internal system state because it encountered a fatal error or was cancelled by the user.</span></span>  <span data-ttu-id="4e421-108">"Rollback" verweist nicht auf Benutzerzustand.</span><span class="sxs-lookup"><span data-stu-id="4e421-108">"RollingBack" does not refer to user state.</span></span>  <span data-ttu-id="4e421-109">Z. B. wenn für einen Befehl vom Typ TestCommandType.PartitionDataLoss CancelTestCommandAsync() aufgerufen wird, bedeutet der Status "Rollback" nicht, dass Dienstdaten (vorausgesetzt, dass der Befehl weit genug fortgeschritten ist, zu Datenverlust führen) wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="4e421-109">For example, if CancelTestCommandAsync() is called on a command of type TestCommandType.PartitionDataLoss, a state of "RollingBack" does not mean service data is being restored (assuming the command has progressed far enough to cause data loss).</span></span>  
            <span data-ttu-id="4e421-110">Dies bedeutet, dass das System wieder/bereinigen internen Systemstatus, die mit dem Befehl verknüpfte zusammenfassen.</span><span class="sxs-lookup"><span data-stu-id="4e421-110">It means the system is rolling back/cleaning up internal system state associated with the command.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.TestCommandProgressState Running = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.TestCommandProgressState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 1" Usage="System.Fabric.TestCommandProgressState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e421-111">Der Testbefehl wird ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="4e421-111">The test command is in progress.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>