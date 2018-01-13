<Type Name="ReplicatorStatus" FullName="System.Fabric.Query.ReplicatorStatus">
  <TypeSignature Language="C#" Value="public abstract class ReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ReplicatorStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ReplicatorStatus" />
  <TypeSignature Language="F#" Value="type ReplicatorStatus = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.SecondaryReplicatorStatus))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.PrimaryReplicatorStatus))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Stellt Statistiken zum Service Fabric Replikator bereit.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ReplicatorStatus (System.Fabric.ReplicaRole role);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.ReplicaRole role) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ReplicatorStatus.#ctor(System.Fabric.ReplicaRole)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (role As ReplicaRole)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.ReplicatorStatus : System.Fabric.ReplicaRole -&gt; System.Fabric.Query.ReplicatorStatus" Usage="new System.Fabric.Query.ReplicatorStatus role" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="role" Type="System.Fabric.ReplicaRole" />
      </Parameters>
      <Docs>
        <param name="role">Die replikatrolle.</param>
        <summary>
            Basis für primäre und sekundäre Replikatoren ReplicatorStatus-Struktur
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>