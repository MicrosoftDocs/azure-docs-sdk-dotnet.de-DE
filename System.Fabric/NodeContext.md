<Type Name="NodeContext" FullName="System.Fabric.NodeContext">
  <TypeSignature Language="C#" Value="public class NodeContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeContext" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeContext" />
  <TypeSignature Language="F#" Value="type NodeContext = class" />
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
      <para>Gibt die Kontextinformationen für einen Service Fabric-Knoten, z. B. Name, ID, Knoten Knotentyp usw. an.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeContext (string nodeName, System.Fabric.NodeId nodeId, System.Numerics.BigInteger nodeInstanceId, string nodeType, string ipAddressOrFQDN);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeName, class System.Fabric.NodeId nodeId, valuetype System.Numerics.BigInteger nodeInstanceId, string nodeType, string ipAddressOrFQDN) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeContext.#ctor(System.String,System.Fabric.NodeId,System.Numerics.BigInteger,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.NodeContext : string * System.Fabric.NodeId * System.Numerics.BigInteger * string * string -&gt; System.Fabric.NodeContext" Usage="new System.Fabric.NodeContext (nodeName, nodeId, nodeInstanceId, nodeType, ipAddressOrFQDN)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Fabric.NodeId" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
        <Parameter Name="nodeType" Type="System.String" />
        <Parameter Name="ipAddressOrFQDN" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">Der Knotenname.</param>
        <param name="nodeId">Die Knoten-ID.</param>
        <param name="nodeInstanceId">Die Instanz-Id von Knoten.</param>
        <param name="nodeType">Der Knotentyp.</param>
        <param name="ipAddressOrFQDN">Die IP-Adresse oder FQDN des Knotens.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.NodeContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDirectory">
      <MemberSignature Language="C#" Value="public string GetDirectory (string logicalDirectoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetDirectory(string logicalDirectoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.NodeContext.GetDirectory(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDirectory (logicalDirectoryName As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetDirectory : string -&gt; string" Usage="nodeContext.GetDirectory logicalDirectoryName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="logicalDirectoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="logicalDirectoryName">To be added.</param>
        <summary>
            Ruft den Verzeichnispfad für das Verzeichnis auf Ebene des Knotens ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddressOrFQDN">
      <MemberSignature Language="C#" Value="public string IPAddressOrFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddressOrFQDN" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.IPAddressOrFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IPAddressOrFQDN As String" />
      <MemberSignature Language="F#" Value="member this.IPAddressOrFQDN : string" Usage="System.Fabric.NodeContext.IPAddressOrFQDN" />
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
          <para>Ruft die IP-Adresse oder den vollständig qualifizierten Domänennamen des Knotens ab.</para>
        </summary>
        <value>
          <para>Gibt die IP-Adresse oder den vollständig qualifizierten Domänennamen des Knotens zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.NodeContext.NodeId" />
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
          <para>Ruft die Knoten-ID.</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.NodeContext.NodeInstanceId" />
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
          <para>Ruft die Instanz-ID von Knoten, die die Knoten eindeutig identifiziert.</para>
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.NodeContext.NodeName" />
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
          <para>Ruft den Knotennamen ab.</para>
        </summary>
        <value>
          <para>Gibt den Knotennamen zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeType">
      <MemberSignature Language="C#" Value="public string NodeType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.NodeContext.NodeType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeType As String" />
      <MemberSignature Language="F#" Value="member this.NodeType : string" Usage="System.Fabric.NodeContext.NodeType" />
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
          <para>Ruft den Knotentyp ab.</para>
        </summary>
        <value>
          <para>Gibt den Knotenzeichenfolge zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>