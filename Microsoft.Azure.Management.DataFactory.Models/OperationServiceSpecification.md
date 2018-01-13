<Type Name="OperationServiceSpecification" FullName="Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification">
  <TypeSignature Language="C#" Value="public class OperationServiceSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationServiceSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationServiceSpecification" />
  <TypeSignature Language="F#" Value="type OperationServiceSpecification = class" />
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
            <span data-ttu-id="997eb-101">Details zu einem Dienstvorgang.</span><span class="sxs-lookup"><span data-stu-id="997eb-101">Details about a service operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationServiceSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.#ctor" />
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
            <span data-ttu-id="997eb-102">Initialisiert eine neue Instanz der OperationServiceSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="997eb-102">Initializes a new instance of the OperationServiceSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationServiceSpecification (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; logSpecifications = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; metricSpecifications = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; logSpecifications, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; metricSpecifications) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification},System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional logSpecifications As IList(Of OperationLogSpecification) = null, Optional metricSpecifications As IList(Of OperationMetricSpecification) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification" Usage="new Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification (logSpecifications, metricSpecifications)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="logSpecifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt;" />
        <Parameter Name="metricSpecifications" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt;" />
      </Parameters>
      <Docs>
        <param name="logSpecifications"><span data-ttu-id="997eb-103">Informationen zu Vorgängen, die im Zusammenhang mit der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="997eb-103">Details about operations related to logs.</span></span></param>
        <param name="metricSpecifications"><span data-ttu-id="997eb-104">Details zu Vorgängen im Zusammenhang mit Metriken.</span><span class="sxs-lookup"><span data-stu-id="997eb-104">Details about operations related to metrics.</span></span></param>
        <summary>
            <span data-ttu-id="997eb-105">Initialisiert eine neue Instanz der OperationServiceSpecification-Klasse.</span><span class="sxs-lookup"><span data-stu-id="997eb-105">Initializes a new instance of the OperationServiceSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogSpecifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; LogSpecifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; LogSpecifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.LogSpecifications" />
      <MemberSignature Language="VB.NET" Value="Public Property LogSpecifications As IList(Of OperationLogSpecification)" />
      <MemberSignature Language="F#" Value="member this.LogSpecifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.LogSpecifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logSpecifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationLogSpecification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="997eb-106">Abrufen oder Festlegen von Informationen zu Vorgängen, die im Zusammenhang mit der Protokolle.</span><span class="sxs-lookup"><span data-stu-id="997eb-106">Gets or sets details about operations related to logs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricSpecifications">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; MetricSpecifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; MetricSpecifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.MetricSpecifications" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricSpecifications As IList(Of OperationMetricSpecification)" />
      <MemberSignature Language="F#" Value="member this.MetricSpecifications : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.OperationServiceSpecification.MetricSpecifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricSpecifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.OperationMetricSpecification&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="997eb-107">Ruft ab, oder legt Sie Details zu Vorgängen im Zusammenhang mit Metriken fest.</span><span class="sxs-lookup"><span data-stu-id="997eb-107">Gets or sets details about operations related to metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>