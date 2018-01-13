<Type Name="PipelineRunQueryFilter" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter">
  <TypeSignature Language="C#" Value="public class PipelineRunQueryFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRunQueryFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRunQueryFilter" />
  <TypeSignature Language="F#" Value="type PipelineRunQueryFilter = class" />
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
            <span data-ttu-id="96dd4-101">Filter-Abfrageoption für das Auflisten von Pipeline ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="96dd4-101">Query filter option for listing pipeline runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.#ctor" />
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
            <span data-ttu-id="96dd4-102">Initialisiert eine neue Instanz der PipelineRunQueryFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="96dd4-102">Initializes a new instance of the PipelineRunQueryFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryFilter (string operand, string operatorProperty, System.Collections.Generic.IList&lt;string&gt; values);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string operand, string operatorProperty, class System.Collections.Generic.IList`1&lt;string&gt; values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.#ctor(System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operand As String, operatorProperty As String, values As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter : string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter (operand, operatorProperty, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operand" Type="System.String" />
        <Parameter Name="operatorProperty" Type="System.String" />
        <Parameter Name="values" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="operand"><span data-ttu-id="96dd4-103">Name des Parameters für Filter verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="96dd4-103">Parameter name to be used for filter.</span></span>
            <span data-ttu-id="96dd4-104">Folgende Werte sind möglich: 'PipelineName', 'Status', 'RunStart', "RunEnd"</span><span class="sxs-lookup"><span data-stu-id="96dd4-104">Possible values include: 'PipelineName', 'Status', 'RunStart', 'RunEnd'</span></span></param>
        <param name="operatorProperty"><span data-ttu-id="96dd4-105">Operator für Filter verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="96dd4-105">Operator to be used for filter.</span></span>
            <span data-ttu-id="96dd4-106">Folgende Werte sind möglich: "Equals", "Ungleich", "In", "NotIn"</span><span class="sxs-lookup"><span data-stu-id="96dd4-106">Possible values include: 'Equals', 'NotEquals', 'In', 'NotIn'</span></span></param>
        <param name="values"><span data-ttu-id="96dd4-107">Liste der Filterwerte.</span><span class="sxs-lookup"><span data-stu-id="96dd4-107">List of filter values.</span></span></param>
        <summary>
            <span data-ttu-id="96dd4-108">Initialisiert eine neue Instanz der PipelineRunQueryFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="96dd4-108">Initializes a new instance of the PipelineRunQueryFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operand">
      <MemberSignature Language="C#" Value="public string Operand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Operand" />
      <MemberSignature Language="VB.NET" Value="Public Property Operand As String" />
      <MemberSignature Language="F#" Value="member this.Operand : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Operand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96dd4-109">Ruft ab, oder legt ihn fest Parametername für Filter verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="96dd4-109">Gets or sets parameter name to be used for filter.</span></span> <span data-ttu-id="96dd4-110">Folgende Werte sind möglich: 'PipelineName', 'Status', 'RunStart', "RunEnd"</span><span class="sxs-lookup"><span data-stu-id="96dd4-110">Possible values include: 'PipelineName', 'Status', 'RunStart', 'RunEnd'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public string OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As String" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96dd4-111">Ruft ab, oder legt ihn fest Operator für Filter verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="96dd4-111">Gets or sets operator to be used for filter.</span></span> <span data-ttu-id="96dd4-112">Folgende Werte sind möglich: "Equals", "Ungleich", "In", "NotIn"</span><span class="sxs-lookup"><span data-stu-id="96dd4-112">Possible values include: 'Equals', 'NotEquals', 'In', 'NotIn'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineRunQueryFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="96dd4-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="96dd4-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="96dd4-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="96dd4-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryFilter.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="96dd4-115">Ruft ab, oder legt ihn fest Werteliste Filter.</span><span class="sxs-lookup"><span data-stu-id="96dd4-115">Gets or sets list of filter values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>