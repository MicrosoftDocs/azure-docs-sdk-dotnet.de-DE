<Type Name="StatefulServiceUpdateDescription" FullName="System.Fabric.Description.StatefulServiceUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class StatefulServiceUpdateDescription : System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulServiceUpdateDescription extends System.Fabric.Description.ServiceUpdateDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.StatefulServiceUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulServiceUpdateDescription&#xA;Inherits ServiceUpdateDescription" />
  <TypeSignature Language="F#" Value="type StatefulServiceUpdateDescription = class&#xA;    inherit ServiceUpdateDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.ServiceUpdateDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Stellt die <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> , dient zum Ändern der <see cref="T:System.Fabric.Description.StatefulServiceDescription" /> eines zurzeit ausgeführten Diensts über <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />. Die angegebenen Eigenschaften werden auf den ausgeführten Dienst angewendet werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StatefulServiceUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.StatefulServiceUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> Klasse mit keine Eigenschaften festgelegt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReplicaSetSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReplicaSetSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinReplicaSetSize : Nullable&lt;int&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> von <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> des <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Siehe <see cref="P:System.Fabric.Description.StatefulServiceDescription.MinReplicaSetSize" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="QuorumLossWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; QuorumLossWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; QuorumLossWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property QuorumLossWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.QuorumLossWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" /> von <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.QuorumLossWaitDuration" /> des <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Siehe <see cref="P:System.Fabric.Description.StatefulServiceDescription.QuorumLossWaitDuration" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaRestartWaitDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; ReplicaRestartWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; ReplicaRestartWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaRestartWaitDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.ReplicaRestartWaitDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" /> von <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.ReplicaRestartWaitDuration" /> des <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Siehe <see cref="P:System.Fabric.Description.StatefulServiceDescription.ReplicaRestartWaitDuration" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="StandByReplicaKeepDuration">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StandByReplicaKeepDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StandByReplicaKeepDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property StandByReplicaKeepDuration As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StandByReplicaKeepDuration : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" /> von <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" /> des <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Siehe <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.StandByReplicaKeepDuration" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetReplicaSetSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetReplicaSetSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetReplicaSetSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetReplicaSetSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetReplicaSetSize : Nullable&lt;int&gt; with get, set" Usage="System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> von <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" /> ab oder legt ihn fest.</para>
        </summary>
        <value>
          <para>Der <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> des <see cref="T:System.Fabric.Description.StatefulServiceUpdateDescription" />.</para>
        </value>
        <remarks>
          <para>Weitere Informationen finden Sie unter <see cref="P:System.Fabric.Description.StatefulServiceDescription.TargetReplicaSetSize" />.</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>