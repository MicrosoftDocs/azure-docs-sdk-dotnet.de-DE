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
            <span data-ttu-id="c9e03-101">Verwaltet die Runtime Integrationsstatus.</span><span class="sxs-lookup"><span data-stu-id="c9e03-101">Managed integration runtime status.</span></span>
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
            <span data-ttu-id="c9e03-102">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c9e03-102">Initializes a new instance of the ManagedIntegrationRuntimeStatus class.</span></span>
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
        <param name="additionalProperties"><span data-ttu-id="c9e03-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="c9e03-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="state"><span data-ttu-id="c9e03-104">Der Status der integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="c9e03-104">The state of integration runtime.</span></span> <span data-ttu-id="c9e03-105">Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"</span><span class="sxs-lookup"><span data-stu-id="c9e03-105">Possible values include: 'Initial', 'Stopped', 'Started', 'Starting', 'Stopping', 'NeedRegistration', 'Online', 'Limited', 'Offline'</span></span></param>
        <param name="createTime"><span data-ttu-id="c9e03-106">Der Zeitpunkt, zu dem der integrationslaufzeit erstellt wurde, im ISO8601-format.</span><span class="sxs-lookup"><span data-stu-id="c9e03-106">The time at which the integration runtime was created, in ISO8601 format.</span></span></param>
        <param name="nodes"><span data-ttu-id="c9e03-107">Die Liste der Knoten für die Laufzeit verwaltete Integration.</span><span class="sxs-lookup"><span data-stu-id="c9e03-107">The list of nodes for managed integration runtime.</span></span></param>
        <param name="otherErrors"><span data-ttu-id="c9e03-108">Auf diese integrationslaufzeit aufgetretenen Fehler.</span><span class="sxs-lookup"><span data-stu-id="c9e03-108">The errors that occurred on this integration runtime.</span></span></param>
        <param name="lastOperation"><span data-ttu-id="c9e03-109">Das letzte vorgangsergebnis, das auf diesem integrationslaufzeit aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="c9e03-109">The last operation result that occurred on this integration runtime.</span></span></param>
        <summary>
            <span data-ttu-id="c9e03-110">Initialisiert eine neue Instanz der ManagedIntegrationRuntimeStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c9e03-110">Initializes a new instance of the ManagedIntegrationRuntimeStatus class.</span></span>
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
            <span data-ttu-id="c9e03-111">Ruft den Zeitpunkt, zu dem der integrationslaufzeit im ISO8601-Format erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="c9e03-111">Gets the time at which the integration runtime was created, in ISO8601 format.</span></span>
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
            <span data-ttu-id="c9e03-112">Ruft das letzte Ergebnis des Vorgangs, das auf diesem integrationslaufzeit aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="c9e03-112">Gets the last operation result that occurred on this integration runtime.</span></span>
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
            <span data-ttu-id="c9e03-113">Ruft die Liste der Knoten für verwaltete integrationslaufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="c9e03-113">Gets the list of nodes for managed integration runtime.</span></span>
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
            <span data-ttu-id="c9e03-114">Ruft die Fehler, die auf diesem integrationslaufzeit aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="c9e03-114">Gets the errors that occurred on this integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>