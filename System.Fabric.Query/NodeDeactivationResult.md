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
      <para>Enthält die ausführlichen Deaktivierungsinformationen zu einem Knoten.</para>
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
          <para>Ein Knoten kann von mehreren Aufgaben gleichzeitig deaktiviert werden. Jede Aufgabe kann eine andere knotendeaktivierungsabsicht angegeben werden. In diesem Fall effektive Absicht ist höchste Absicht aller deaktivierungsaufgaben, in denen ist Sortierung als Anhalten definiert &lt; Neustart &lt; RemoveData.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.NodeDeactivationIntent" />zurück.</para>
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
            Ruft eine Liste von sicherheitsüberprüfungen, die derzeit auftritt.
            </para>
        </summary>
        <value>
          <para>Die Liste der fehlerhaften Sicherheit überprüft.</para>
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
          <para>Gibt den deaktivierungsstatus eines Knotens an.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.NodeDeactivationStatus" />zurück.</para>
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
          <para>Enthält Informationen zu allen deaktivierungsaufgaben für einen Knoten.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Collections.Generic.IList`1" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>