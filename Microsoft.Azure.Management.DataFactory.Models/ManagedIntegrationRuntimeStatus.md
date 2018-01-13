<Type Name="ManagedIntegrationRuntimeStatus" FullName="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus">
  <TypeSignature Language="C#" Value="public class ManagedIntegrationRuntimeStatus : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedIntegrationRuntimeStatus extends Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedIntegrationRuntimeStatus&#xA;Inherits IntegrationRuntimeStatus" />
  <TypeSignature Language="F#" Value="type ManagedIntegrationRuntimeStatus = class&#xA;    inherit IntegrationRuntimeStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Managed")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Verwaltet die Runtime Integrationsstatus.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.#ctor" />
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
            Initialisiert eine neue Instanz der ManagedIntegrationRuntimeStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntimeStatus (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string state = null, Nullable&lt;DateTime&gt; createTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt; nodes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; otherErrors = null, Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult lastOperation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt; nodes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; otherErrors, class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult lastOperation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError},Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional state As String = null, Optional createTime As Nullable(Of DateTime) = null, Optional nodes As IList(Of ManagedIntegrationRuntimeNode) = null, Optional otherErrors As IList(Of ManagedIntegrationRuntimeError) = null, Optional lastOperation As ManagedIntegrationRuntimeOperationResult = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; * Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult -&gt; Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus" Usage="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus (additionalProperties, state, createTime, nodes, otherErrors, lastOperation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="createTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="nodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt;" />
        <Parameter Name="otherErrors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt;" />
        <Parameter Name="lastOperation" Type="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="state">Der Status der integrationslaufzeit. Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"</param>
        <param name="createTime">Der Zeitpunkt, zu dem der integrationslaufzeit erstellt wurde, im ISO8601-format.</param>
        <param name="nodes">Die Liste der Knoten für die Laufzeit verwaltete Integration.</param>
        <param name="otherErrors">Auf diese integrationslaufzeit aufgetretenen Fehler.</param>
        <param name="lastOperation">Das letzte vorgangsergebnis, das auf diesem integrationslaufzeit aufgetreten sind.</param>
        <summary>
            Initialisiert eine neue Instanz der ManagedIntegrationRuntimeStatus-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.CreateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreateTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.CreateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.createTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, zu dem der integrationslaufzeit im ISO8601-Format erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOperation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult LastOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult LastOperation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.LastOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOperation As ManagedIntegrationRuntimeOperationResult" />
      <MemberSignature Language="F#" Value="member this.LastOperation : Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.LastOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.lastOperation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeOperationResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das letzte Ergebnis des Vorgangs, das auf diesem integrationslaufzeit aufgetreten sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt; Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt; Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Nodes As IList(Of ManagedIntegrationRuntimeNode)" />
      <MemberSignature Language="F#" Value="member this.Nodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.nodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeNode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Knoten für verwaltete integrationslaufzeit ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OtherErrors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; OtherErrors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt; OtherErrors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.OtherErrors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OtherErrors As IList(Of ManagedIntegrationRuntimeError)" />
      <MemberSignature Language="F#" Value="member this.OtherErrors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeStatus.OtherErrors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.otherErrors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntimeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Fehler, die auf diesem integrationslaufzeit aufgetreten sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>