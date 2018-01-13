<Type Name="NodeDeactivationResult" FullName="System.Fabric.Query.NodeDeactivationResult">
  <TypeSignature Language="C#" Value="public sealed class NodeDeactivationResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeDeactivationResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeDeactivationResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeDeactivationResult" />
  <TypeSignature Language="F#" Value="type NodeDeactivationResult = class" />
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
      <para><span data-ttu-id="4b131-101">Enthält die ausführlichen Deaktivierungsinformationen zu einem Knoten.</span><span class="sxs-lookup"><span data-stu-id="4b131-101">Contains the detailed deactivation information about a node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EffectiveIntent">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeDeactivationIntent EffectiveIntent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeDeactivationIntent EffectiveIntent" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.EffectiveIntent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EffectiveIntent As NodeDeactivationIntent" />
      <MemberSignature Language="F#" Value="member this.EffectiveIntent : System.Fabric.NodeDeactivationIntent" Usage="System.Fabric.Query.NodeDeactivationResult.EffectiveIntent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationIntent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4b131-102">Ein Knoten kann von mehreren Aufgaben gleichzeitig deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="4b131-102">A node may get deactivated by multiple tasks at the same time.</span></span> <span data-ttu-id="4b131-103">Jede Aufgabe kann eine andere knotendeaktivierungsabsicht angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4b131-103">Each task may specify a different node deactivation intent.</span></span> <span data-ttu-id="4b131-104">In diesem Fall effektive Absicht ist höchste Absicht aller deaktivierungsaufgaben, in denen ist Sortierung als Anhalten definiert &lt; Neustart &lt; RemoveData.</span><span class="sxs-lookup"><span data-stu-id="4b131-104">In this case, effective intent is highest intent among all deactivation tasks, where ordering is defined as Pause &lt; Restart &lt; RemoveData.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4b131-105">Gibt <see cref="T:System.Fabric.NodeDeactivationIntent" />zurück.</span><span class="sxs-lookup"><span data-stu-id="4b131-105">Returns <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingSafetyChecks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt; PendingSafetyChecks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.SafetyCheck&gt; PendingSafetyChecks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.PendingSafetyChecks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingSafetyChecks As IList(Of SafetyCheck)" />
      <MemberSignature Language="F#" Value="member this.PendingSafetyChecks : System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt;" Usage="System.Fabric.Query.NodeDeactivationResult.PendingSafetyChecks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.SafetyCheck&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="4b131-106">Ruft eine Liste von sicherheitsüberprüfungen, die derzeit auftritt.</span><span class="sxs-lookup"><span data-stu-id="4b131-106">Gets a list of safety checks that are currently failing.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="4b131-107">Die Liste der fehlerhaften Sicherheit überprüft.</span><span class="sxs-lookup"><span data-stu-id="4b131-107">The list of failing safety checks.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeDeactivationStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeDeactivationStatus Status" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As NodeDeactivationStatus" />
      <MemberSignature Language="F#" Value="member this.Status : System.Fabric.NodeDeactivationStatus" Usage="System.Fabric.Query.NodeDeactivationResult.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeDeactivationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4b131-108">Gibt den deaktivierungsstatus eines Knotens an.</span><span class="sxs-lookup"><span data-stu-id="4b131-108">Specifies the deactivation status for a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4b131-109">Gibt <see cref="T:System.Fabric.NodeDeactivationStatus" />zurück.</span><span class="sxs-lookup"><span data-stu-id="4b131-109">Returns <see cref="T:System.Fabric.NodeDeactivationStatus" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt; Tasks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.NodeDeactivationTask&gt; Tasks" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeDeactivationResult.Tasks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tasks As IList(Of NodeDeactivationTask)" />
      <MemberSignature Language="F#" Value="member this.Tasks : System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt;" Usage="System.Fabric.Query.NodeDeactivationResult.Tasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.NodeDeactivationTask&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="4b131-110">Enthält Informationen zu allen deaktivierungsaufgaben für einen Knoten.</span><span class="sxs-lookup"><span data-stu-id="4b131-110">Contains information about all the node deactivation tasks for a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4b131-111">Gibt <see cref="T:System.Collections.Generic.IList`1" />zurück.</span><span class="sxs-lookup"><span data-stu-id="4b131-111">Returns <see cref="T:System.Collections.Generic.IList`1" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>