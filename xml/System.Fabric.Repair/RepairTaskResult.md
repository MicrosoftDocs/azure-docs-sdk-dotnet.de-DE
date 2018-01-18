<Type Name="RepairTaskResult" FullName="System.Fabric.Repair.RepairTaskResult">
  <TypeSignature Language="C#" Value="public enum RepairTaskResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RepairTaskResult extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Repair.RepairTaskResult" />
  <TypeSignature Language="VB.NET" Value="Public Enum RepairTaskResult" />
  <TypeSignature Language="F#" Value="type RepairTaskResult = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>System.Flags</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="230ff-101">Gibt das Ergebnis des Tasks "Reparieren".</span><span class="sxs-lookup"><span data-stu-id="230ff-101">Specifies the result of the repair task.</span></span></para>
      <para><span data-ttu-id="230ff-102">Dieser Typ unterstützt die Service Fabric-Plattform; Es ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="230ff-102">This type supports the Service Fabric platform; it is not meant to be used directly from your code.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Cancelled">
      <MemberSignature Language="C#" Value="Cancelled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Cancelled = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Cancelled" />
      <MemberSignature Language="VB.NET" Value="Cancelled" />
      <MemberSignature Language="F#" Value="Cancelled = 2" Usage="System.Fabric.Repair.RepairTaskResult.Cancelled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-103">Gibt an, dass die reparaturaufgabe vor der Ausführung abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="230ff-103">Indicates that the repair task was cancelled prior to execution.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Failed = int32(8)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 8" Usage="System.Fabric.Repair.RepairTaskResult.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-104">Gibt an, dass ein Fehler, während der Ausführung des Tasks "Reparieren aufgetreten".</span><span class="sxs-lookup"><span data-stu-id="230ff-104">Indicates that there was a failure during execution of the repair task.</span></span> <span data-ttu-id="230ff-105">Aufwand ist möglicherweise ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="230ff-105">Some work may have been performed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Interrupted">
      <MemberSignature Language="C#" Value="Interrupted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Interrupted = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Interrupted" />
      <MemberSignature Language="VB.NET" Value="Interrupted" />
      <MemberSignature Language="F#" Value="Interrupted = 4" Usage="System.Fabric.Repair.RepairTaskResult.Interrupted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-106">Gibt an, dass die Ausführung des Tasks "Reparieren" durch eine abbruchanforderung unterbrochen wurde, nachdem einige Arbeit bereits ausgeführt worden wäre.</span><span class="sxs-lookup"><span data-stu-id="230ff-106">Indicates that execution of the repair task was interrupted by a cancellation request after some work had already been performed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.Repair.RepairTaskResult.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-107">Gibt an, dass die Reparatur Taskergebnis ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="230ff-107">Indicates that the repair task result is invalid.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Pending">
      <MemberSignature Language="C#" Value="Pending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Pending = int32(16)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Pending" />
      <MemberSignature Language="VB.NET" Value="Pending" />
      <MemberSignature Language="F#" Value="Pending = 16" Usage="System.Fabric.Repair.RepairTaskResult.Pending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>16</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-108">Gibt an, dass die Reparatur Taskergebnis nicht noch verfügbar ist, weil die reparaturaufgabe nicht Ausführung beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="230ff-108">Indicates that the repair task result is not yet available, because the repair task has not finished executing.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="Succeeded" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.Repair.RepairTaskResult Succeeded = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Repair.RepairTaskResult.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Succeeded" />
      <MemberSignature Language="F#" Value="Succeeded = 1" Usage="System.Fabric.Repair.RepairTaskResult.Succeeded" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Repair.RepairTaskResult</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="230ff-109">Gibt an, dass die reparaturaufgabe Ausführung erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="230ff-109">Indicates that the repair task completed execution successfully.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>