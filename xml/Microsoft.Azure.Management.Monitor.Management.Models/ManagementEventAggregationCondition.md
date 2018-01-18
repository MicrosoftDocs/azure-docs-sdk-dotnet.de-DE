<Type Name="ManagementEventAggregationCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition">
  <TypeSignature Language="C#" Value="public class ManagementEventAggregationCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagementEventAggregationCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagementEventAggregationCondition" />
  <TypeSignature Language="F#" Value="type ManagementEventAggregationCondition = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="630b9-101">Legt fest, wie die erfassten Daten im Zeitverlauf kombiniert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="630b9-101">How the data that is collected should be combined over time.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementEventAggregationCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="630b9-102">Initialisiert eine neue Instanz der ManagementEventAggregationCondition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="630b9-102">Initializes a new instance of the ManagementEventAggregationCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagementEventAggregationCondition (Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; operatorProperty = null, Nullable&lt;double&gt; threshold = null, Nullable&lt;TimeSpan&gt; windowSize = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; operatorProperty, valuetype System.Nullable`1&lt;float64&gt; threshold, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; windowSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.#ctor(System.Nullable{Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator},System.Nullable{System.Double},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional operatorProperty As Nullable(Of ConditionOperator) = null, Optional threshold As Nullable(Of Double) = null, Optional windowSize As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; * Nullable&lt;double&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition (operatorProperty, threshold, windowSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operatorProperty" Type="System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt;" />
        <Parameter Name="threshold" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="windowSize" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="operatorProperty"><span data-ttu-id="630b9-103">der Bedingungsoperator.</span><span class="sxs-lookup"><span data-stu-id="630b9-103">the condition operator.</span></span> <span data-ttu-id="630b9-104">Folgende Werte sind möglich: "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"</span><span class="sxs-lookup"><span data-stu-id="630b9-104">Possible values include: 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span></param>
        <param name="threshold"><span data-ttu-id="630b9-105">Der Schwellenwert, der die Warnung aktiviert.</span><span class="sxs-lookup"><span data-stu-id="630b9-105">The threshold value that activates the alert.</span></span></param>
        <param name="windowSize"><span data-ttu-id="630b9-106">die Zeitspanne (in Dauer ISO 8601-Format), die verwendet wird, auf Grundlage des Schwellenwerts Aktivität zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="630b9-106">the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="630b9-107">Wenn angegeben, muss zwischen 5 Minuten und 1 Tag sein.</span><span class="sxs-lookup"><span data-stu-id="630b9-107">If specified then it must be between 5 minutes and 1 day.</span></span></param>
        <summary>
            <span data-ttu-id="630b9-108">Initialisiert eine neue Instanz der ManagementEventAggregationCondition-Klasse.</span><span class="sxs-lookup"><span data-stu-id="630b9-108">Initializes a new instance of the ManagementEventAggregationCondition class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As Nullable(Of ConditionOperator)" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Monitor.Management.Models.ConditionOperator&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="630b9-109">Ruft ab, oder legt ihn fest-bedingungs-Operator.</span><span class="sxs-lookup"><span data-stu-id="630b9-109">Gets or sets the condition operator.</span></span> <span data-ttu-id="630b9-110">Folgende Werte sind möglich: "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"</span><span class="sxs-lookup"><span data-stu-id="630b9-110">Possible values include: 'GreaterThan', 'GreaterThanOrEqual', 'LessThan', 'LessThanOrEqual'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threshold">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Threshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Threshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.Threshold" />
      <MemberSignature Language="VB.NET" Value="Public Property Threshold As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Threshold : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.Threshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="threshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="630b9-111">Ruft ab oder legt den Schwellenwert-Wert, der die Warnung aktiviert.</span><span class="sxs-lookup"><span data-stu-id="630b9-111">Gets or sets the threshold value that activates the alert.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; WindowSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; WindowSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.WindowSize" />
      <MemberSignature Language="VB.NET" Value="Public Property WindowSize As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.WindowSize : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ManagementEventAggregationCondition.WindowSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="windowSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="630b9-112">Ruft ab oder legt die Zeitspanne (in Dauer ISO 8601-Format) an, die verwendet wird, auf Grundlage des Schwellenwerts Aktivität zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="630b9-112">Gets or sets the period of time (in ISO 8601 duration format) that is used to monitor alert activity based on the threshold.</span></span> <span data-ttu-id="630b9-113">Wenn angegeben, muss zwischen 5 Minuten und 1 Tag sein.</span><span class="sxs-lookup"><span data-stu-id="630b9-113">If specified then it must be between 5 minutes and 1 day.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>