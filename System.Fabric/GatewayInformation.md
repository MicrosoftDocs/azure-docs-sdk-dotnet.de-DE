<Type Name="GatewayInformation" FullName="System.Fabric.GatewayInformation">
  <TypeSignature Language="C#" Value="public sealed class GatewayInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit GatewayInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.GatewayInformation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class GatewayInformation" />
  <TypeSignature Language="F#" Value="type GatewayInformation = class" />
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
      <para>Enthält Informationen zur Kennzeichnung von eines Service Fabric-Knotens im Cluster an.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeAddress">
      <MemberSignature Language="C#" Value="public string NodeAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeAddress As String" />
      <MemberSignature Language="F#" Value="member this.NodeAddress : string" Usage="System.Fabric.GatewayInformation.NodeAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Adresse, die Service Fabric-Clients, beim Verbinden mit diesem Knoten (wie in der Cluster-Manifest angegeben verwenden).</para>
        </summary>
        <value>
          <para>Die Adresse, die Service Fabric-Clients, beim Verbinden mit diesem Knoten (wie in der Cluster-Manifest angegeben verwenden).</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.GatewayInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Der eindeutige Bezeichner von Service Fabric intern verwendet wird, um einen Knoten zu identifizieren. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.NodeId" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.GatewayInformation.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Die Instanz von einem Service Fabric-Knoten ändert, wenn der Knoten neu gestartet wird.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.GatewayInformation.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.GatewayInformation.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Der angezeigte Name des Service Fabric-Knotens (definiert in den Cluster Manifest) verwendet, um die Knoten-ID zu generieren.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.String" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>