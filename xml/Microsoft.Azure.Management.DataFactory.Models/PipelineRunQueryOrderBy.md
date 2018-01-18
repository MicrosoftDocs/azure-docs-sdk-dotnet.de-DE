<Type Name="PipelineRunQueryOrderBy" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy">
  <TypeSignature Language="C#" Value="public class PipelineRunQueryOrderBy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRunQueryOrderBy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRunQueryOrderBy" />
  <TypeSignature Language="F#" Value="type PipelineRunQueryOrderBy = class" />
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
            <span data-ttu-id="a8915-101">Ein Objekt, geben Sie die Reihenfolge von Optionen für das Angebot Pipeline ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="a8915-101">An object to provide order by options for listing pipeline runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryOrderBy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.#ctor" />
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
            <span data-ttu-id="a8915-102">Initialisiert eine neue Instanz der PipelineRunQueryOrderBy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a8915-102">Initializes a new instance of the PipelineRunQueryOrderBy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRunQueryOrderBy (string orderBy, string order);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string orderBy, string order) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (orderBy As String, order As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy : string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy (orderBy, order)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="orderBy" Type="System.String" />
        <Parameter Name="order" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="orderBy"><span data-ttu-id="a8915-103">Name des Parameters für die Order by-verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a8915-103">Parameter name to be used for order by.</span></span>
            <span data-ttu-id="a8915-104">Folgende Werte sind möglich: "RunStart", "RunEnd"</span><span class="sxs-lookup"><span data-stu-id="a8915-104">Possible values include: 'RunStart', 'RunEnd'</span></span></param>
        <param name="order"><span data-ttu-id="a8915-105">Die Sortierreihenfolge des Parameters.</span><span class="sxs-lookup"><span data-stu-id="a8915-105">Sorting order of the parameter.</span></span> <span data-ttu-id="a8915-106">Folgende Werte sind möglich: "ASC", "DESC"</span><span class="sxs-lookup"><span data-stu-id="a8915-106">Possible values include: 'ASC', 'DESC'</span></span></param>
        <summary>
            <span data-ttu-id="a8915-107">Initialisiert eine neue Instanz der PipelineRunQueryOrderBy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a8915-107">Initializes a new instance of the PipelineRunQueryOrderBy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Order">
      <MemberSignature Language="C#" Value="public string Order { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Order" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.Order" />
      <MemberSignature Language="VB.NET" Value="Public Property Order As String" />
      <MemberSignature Language="F#" Value="member this.Order : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.Order" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="order")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8915-108">Ruft ab, oder legt sie fest, die Sortierreihenfolge des Parameters.</span><span class="sxs-lookup"><span data-stu-id="a8915-108">Gets or sets sorting order of the parameter.</span></span> <span data-ttu-id="a8915-109">Folgende Werte sind möglich: "ASC", "DESC"</span><span class="sxs-lookup"><span data-stu-id="a8915-109">Possible values include: 'ASC', 'DESC'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OrderBy">
      <MemberSignature Language="C#" Value="public string OrderBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OrderBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.OrderBy" />
      <MemberSignature Language="VB.NET" Value="Public Property OrderBy As String" />
      <MemberSignature Language="F#" Value="member this.OrderBy : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.OrderBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="orderBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a8915-110">Ruft ab, oder legt ihn fest Parametername für Order by-verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a8915-110">Gets or sets parameter name to be used for order by.</span></span> <span data-ttu-id="a8915-111">Folgende Werte sind möglich: "RunStart", "RunEnd"</span><span class="sxs-lookup"><span data-stu-id="a8915-111">Possible values include: 'RunStart', 'RunEnd'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRunQueryOrderBy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pipelineRunQueryOrderBy.Validate " />
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
            <span data-ttu-id="a8915-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a8915-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a8915-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a8915-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>