<Type Name="JobPreparationAndReleaseTaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationAndReleaseTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationAndReleaseTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobPreparationAndReleaseTaskExecutionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2201e-101">Der Status des Auftrags Vorbereitung und Auftrag Version Tasks auf einem Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="2201e-101">The status of the Job Preparation and Job Release tasks on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationAndReleaseTaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2201e-102">Initialisiert eine neue Instanz der JobPreparationAndReleaseTaskExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2201e-102">Initializes a new instance of the JobPreparationAndReleaseTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationAndReleaseTaskExecutionInformation (string poolId = null, string nodeId = null, string nodeUrl = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation jobPreparationTaskExecutionInfo = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation jobReleaseTaskExecutionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, string nodeId, string nodeUrl, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation jobPreparationTaskExecutionInfo, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation jobReleaseTaskExecutionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional poolId As String = null, Optional nodeId As String = null, Optional nodeUrl As String = null, Optional jobPreparationTaskExecutionInfo As JobPreparationTaskExecutionInformation = null, Optional jobReleaseTaskExecutionInfo As JobReleaseTaskExecutionInformation = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation : string * string * string * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation (poolId, nodeId, nodeUrl, jobPreparationTaskExecutionInfo, jobReleaseTaskExecutionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeUrl" Type="System.String" />
        <Parameter Name="jobPreparationTaskExecutionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation" />
        <Parameter Name="jobReleaseTaskExecutionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="2201e-103">Die ID des Pools mit dem Computeknoten, auf der dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-103">The ID of the pool containing the compute node to which this entry refers.</span></span></param>
        <param name="nodeId"><span data-ttu-id="2201e-104">Die ID der Compute-Knoten, auf der dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-104">The ID of the compute node to which this entry refers.</span></span></param>
        <param name="nodeUrl"><span data-ttu-id="2201e-105">Die URL des Compute-Knoten, auf der dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-105">The URL of the compute node to which this entry refers.</span></span></param>
        <param name="jobPreparationTaskExecutionInfo"><span data-ttu-id="2201e-106">Informationen zu den Ausführungsstatus des Tasks "Auftrag zur Vorbereitung" auf diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="2201e-106">Information about the execution status of the Job Preparation task on this compute node.</span></span></param>
        <param name="jobReleaseTaskExecutionInfo"><span data-ttu-id="2201e-107">Informationen zu den Ausführungsstatus des Tasks "Auftrag Version" auf diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="2201e-107">Information about the execution status of the Job Release task on this compute node.</span></span></param>
        <summary>
            <span data-ttu-id="2201e-108">Initialisiert eine neue Instanz der JobPreparationAndReleaseTaskExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2201e-108">Initializes a new instance of the JobPreparationAndReleaseTaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTaskExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation JobPreparationTaskExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTaskExecutionInfo As JobPreparationTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTaskExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobPreparationTaskExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTaskExecutionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201e-109">Ruft ab, oder legt Sie Informationen über den Ausführungsstatus des Tasks "Auftrag zur Vorbereitung" auf diesem Computeknoten fest.</span><span class="sxs-lookup"><span data-stu-id="2201e-109">Gets or sets information about the execution status of the Job Preparation task on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTaskExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation JobReleaseTaskExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTaskExecutionInfo As JobReleaseTaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTaskExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.JobReleaseTaskExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTaskExecutionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201e-110">Ruft ab, oder legt fest Informationen über den Ausführungsstatus des Tasks "Auftrag Version" auf diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="2201e-110">Gets or sets information about the execution status of the Job Release task on this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2201e-111">Diese Eigenschaft wird festgelegt, nur dann, wenn der Auftrag Version Task auf den Knoten ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="2201e-111">This property is set only if the Job Release task has run on the node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="2201e-112">Ruft ab oder legt die ID des Compute-Knoten, auf der dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-112">Gets or sets the ID of the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUrl">
      <MemberSignature Language="C#" Value="public string NodeUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeUrl As String" />
      <MemberSignature Language="F#" Value="member this.NodeUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.NodeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201e-113">Ruft ab oder legt die URL des Serverknotens, auf das dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-113">Gets or sets the URL of the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2201e-114">Ruft ab oder legt die ID des Speicherpools, die mit dem Computeknoten, auf der dieser Eintrag verweist.</span><span class="sxs-lookup"><span data-stu-id="2201e-114">Gets or sets the ID of the pool containing the compute node to which this entry refers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationAndReleaseTaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationAndReleaseTaskExecutionInformation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2201e-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2201e-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2201e-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2201e-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>