<Type Name="PoolInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolInformation">
  <TypeSignature Language="C#" Value="public class PoolInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolInformation" />
  <TypeSignature Language="F#" Value="type PoolInformation = class" />
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
            <span data-ttu-id="1a521-101">Gibt an, wie ein Auftrag zu einem Pool zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="1a521-101">Specifies how a job should be assigned to a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor" />
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
            <span data-ttu-id="1a521-102">Initialisiert eine neue Instanz der PoolInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1a521-102">Initializes a new instance of the PoolInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation (string poolId = null, Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string poolId, class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification autoPoolSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation : string * Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolInformation (poolId, autoPoolSpecification)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="autoPoolSpecification" Type="Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification" />
      </Parameters>
      <Docs>
        <param name="poolId"><span data-ttu-id="1a521-103">Die ID des einen vorhandenen Pool.</span><span class="sxs-lookup"><span data-stu-id="1a521-103">The ID of an existing pool.</span></span> <span data-ttu-id="1a521-104">Alle Aufgaben des Auftrags werden auf dem angegebenen Pool ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="1a521-104">All the tasks of the job will run on the specified pool.</span></span></param>
        <param name="autoPoolSpecification"><span data-ttu-id="1a521-105">Merkmale für eine temporäre "Pools".</span><span class="sxs-lookup"><span data-stu-id="1a521-105">Characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="1a521-106">Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.</span><span class="sxs-lookup"><span data-stu-id="1a521-106">The Batch service will create this auto pool when the job is submitted.</span></span></param>
        <summary>
            <span data-ttu-id="1a521-107">Initialisiert eine neue Instanz der PoolInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1a521-107">Initializes a new instance of the PoolInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification AutoPoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolSpecification As AutoPoolSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoPoolSpecification : Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.AutoPoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoPoolSpecification")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AutoPoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1a521-108">Ruft ab oder legt Eigenschaften für einen temporären "Pools".</span><span class="sxs-lookup"><span data-stu-id="1a521-108">Gets or sets characteristics for a temporary 'auto pool'.</span></span> <span data-ttu-id="1a521-109">Der Batch-Dienst wird diese Pools erstellt, wenn der Auftrag übermittelt wird.</span><span class="sxs-lookup"><span data-stu-id="1a521-109">The Batch service will create this auto pool when the job is submitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1a521-110">Fällt die Erstellung des automatischen Pools, der Batch-Dienst verschiebt den Auftrag, um den Status "abgeschlossen", und der Fehler beim Erstellen des Anwendungspools in den Auftrag planen Error-Eigenschaft festgelegt wird.</span><span class="sxs-lookup"><span data-stu-id="1a521-110">If auto pool creation fails, the Batch service moves the job to a completed state, and the pool creation error is set in the job's scheduling error property.</span></span> <span data-ttu-id="1a521-111">Der Batch-Dienst verwaltet die Lebensdauer (sowohl die Erstellung und, es sei denn, "Keepalive" angegeben ist, löschen) des automatischen Pools.</span><span class="sxs-lookup"><span data-stu-id="1a521-111">The Batch service manages the lifetime (both creation and, unless keepAlive is specified, deletion) of the auto pool.</span></span> <span data-ttu-id="1a521-112">Alle Benutzeraktionen, die Einfluss auf die Lebensdauer des Pools, während der Auftrag aktiv ist, werden zu unerwartetem Verhalten führen.</span><span class="sxs-lookup"><span data-stu-id="1a521-112">Any user actions that affect the lifetime of the auto pool while the job is active will result in unexpected behavior.</span></span>
            <span data-ttu-id="1a521-113">Sie müssen die Pool-ID oder die Spezifikation des automatischen Pools, aber nicht beides angeben.</span><span class="sxs-lookup"><span data-stu-id="1a521-113">You must specify either the pool ID or the auto pool specification, but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolInformation.PoolId" />
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
            <span data-ttu-id="1a521-114">Ruft ab oder legt die ID des einen vorhandenen Pool.</span><span class="sxs-lookup"><span data-stu-id="1a521-114">Gets or sets the ID of an existing pool.</span></span> <span data-ttu-id="1a521-115">Alle Aufgaben des Auftrags werden auf dem angegebenen Pool ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="1a521-115">All the tasks of the job will run on the specified pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1a521-116">Sie müssen sicherstellen, dass der Pool verwiesen wird, die von dieser Eigenschaft vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="1a521-116">You must ensure that the pool referenced by this property exists.</span></span>
            <span data-ttu-id="1a521-117">Wenn der Pool nicht, wenn der Batch-Dienst versucht vorhanden ist, einen Auftrag zu planen wird, werden keine Vorgänge für den Auftrag ausgeführt, bis Sie einen Pool mit dieser Id erstellt. Beachten Sie, dass der Batch-Dienst die Anforderung nicht abgelehnt werden. Sie wird Tasks einfach nicht ausgeführt, bis der Pool vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="1a521-117">If the pool does not exist at the time the Batch service tries to schedule a job, no tasks for the job will run until you create a pool with that id. Note that the Batch service will not reject the job request; it will simply not run tasks until the pool exists.</span></span>
            <span data-ttu-id="1a521-118">Sie müssen die Pool-ID oder die Spezifikation des automatischen Pools, aber nicht beides angeben.</span><span class="sxs-lookup"><span data-stu-id="1a521-118">You must specify either the pool ID or the auto pool specification, but not both.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="poolInformation.Validate " />
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
            <span data-ttu-id="1a521-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1a521-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1a521-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1a521-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>