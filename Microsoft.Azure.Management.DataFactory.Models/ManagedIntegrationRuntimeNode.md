<Type Name="ManagedIntegrationRuntimeNode" FullName="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode">
  <TypeSignature Language="C#" Value="public class ManagedIntegrationRuntimeNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedIntegrationRuntimeNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedIntegrationRuntimeNode" />
  <TypeSignature Language="F#" Value="type ManagedIntegrationRuntimeNode = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften des Integration Common Language Runtime-Knoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ManagedIntegrationRuntimeNode-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeNode (string nodeId = null, string status = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; errors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nodeId, string status, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; errors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nodeId As String = null, Optional status As String = null, Optional errors As IList(Of ManagedIntegrationRuntimeError) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode" Usage="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode (nodeId, status, errors)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeId">Der Knoten-Id verwaltete Integration Common Language Runtime.</param>
        <param name="status">Der Status der verwalteten Integration Common Language Runtime-Knoten.
            Folgende Werte sind möglich: "Starten", "Verfügbar", "Recycling", "Nicht verfügbar"</param>
        <param name="errors">Die Fehler, die auf diesem Knoten der Integration-Laufzeit aufgetreten sind.</param>
        <summary>
            Initialisiert eine neue Instanz der ManagedIntegrationRuntimeNode-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ManagedIntegrationRuntimeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft auf oder legt die aufgetretenen Fehler dieser Integration Common Language Runtime-Knoten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die verwaltete Integration Common Language Runtime-Knoten-Id ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die verwaltete Laufzeit Knoten Integrationsstatus ab. Folgende Werte sind möglich: "Starten", "Verfügbar", "Recycling", "Nicht verfügbar"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>