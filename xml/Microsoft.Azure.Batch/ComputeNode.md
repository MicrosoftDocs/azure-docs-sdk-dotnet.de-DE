<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type ComputeNode = class&#xA;    interface IRefreshable&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IRefreshable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ded09-101">Enthält eine Zusammenfassung den Status der Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-101">Summarizes the state of a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string" Usage="Microsoft.Azure.Batch.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-102">Ruft eine nicht transparente Zeichenfolge, die Informationen über den Speicherort des Serverknotens enthält.</span><span class="sxs-lookup"><span data-stu-id="ded09-102">Gets an opaque string that contains information about the location of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-103">Ruft den Zeitpunkt, zu dem dieser Serverknoten dem Pool zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="ded09-103">Gets the time at which this compute node was allocated to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateReferences As IReadOnlyList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-104">Ruft die Liste der Zertifikate, die auf diese Computeknoten installiert.</span><span class="sxs-lookup"><span data-stu-id="ded09-104">Gets the list of certificates installed on this compute node.</span></span> 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateComputeNodeUser">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.ComputeNodeUser CreateComputeNodeUser() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.CreateComputeNodeUser" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateComputeNodeUser () As ComputeNodeUser" />
      <MemberSignature Language="F#" Value="member this.CreateComputeNodeUser : unit -&gt; Microsoft.Azure.Batch.ComputeNodeUser" Usage="computeNode.CreateComputeNodeUser " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeUser</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ded09-105">Instanziiert ein ungebundenes ComputeNodeUser Objekt aufgefüllt, die vom Aufrufer und zum Erstellen eines Benutzerkontos auf den Computeknoten in der Azure Batch-Dienst verwendet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="ded09-105">Instantiates an unbound ComputeNodeUser object to be populated by the caller and used to create a user account on the compute node in the Azure Batch service.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-106">Ein <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" />-Objekt.</span><span class="sxs-lookup"><span data-stu-id="ded09-106">An <see cref="T:Microsoft.Azure.Batch.ComputeNodeUser" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-107">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-107">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="ded09-108">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="ded09-108">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="ded09-109">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="ded09-109">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="ded09-110">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="ded09-110">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUser">
      <MemberSignature Language="C#" Value="public void DeleteComputeNodeUser (string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteComputeNodeUser(string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DeleteComputeNodeUser(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteComputeNodeUser (userName As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUser : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.DeleteComputeNodeUser (userName, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="ded09-111">Der Name des der ComputeNodeUser gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-111">The name of the ComputeNodeUser to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-112">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-112">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-113">Durch Aufruf der angegebenen ComputeNodeUser löschen blockiert.</span><span class="sxs-lookup"><span data-stu-id="ded09-113">Blocking call to delete the specified ComputeNodeUser.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteComputeNodeUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteComputeNodeUserAsync (string userName, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteComputeNodeUserAsync(string userName, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DeleteComputeNodeUserAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteComputeNodeUserAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.DeleteComputeNodeUserAsync (userName, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="ded09-114">Der Name des der ComputeNodeUser gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-114">The name of the ComputeNodeUser to be deleted.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-115">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-115">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-116">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-116">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-117">Startet einen asynchronen Aufruf der angegebenen ComputeNodeUser zu löschen.</span><span class="sxs-lookup"><span data-stu-id="ded09-117">Begins an asynchronous call to delete the specified ComputeNodeUser.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-118">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-118">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableScheduling">
      <MemberSignature Language="C#" Value="public void DisableScheduling (Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableScheduling(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DisableScheduling(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableScheduling (disableComputeNodeSchedulingOption As Nullable(Of DisableComputeNodeSchedulingOption), Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableScheduling : Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.DisableScheduling (disableComputeNodeSchedulingOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="ded09-119">Gibt an, was mit den derzeit ausgeführten Tasks.</span><span class="sxs-lookup"><span data-stu-id="ded09-119">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="ded09-120">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-120">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-121">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-121">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-122">Deaktiviert die aufgabenplanung auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-122">Disables task scheduling on the compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="ded09-123">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ded09-123">This is a blocking operation.</span></span> <span data-ttu-id="ded09-124">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.ComputeNode.DisableSchedulingAsync(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-124">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.ComputeNode.DisableSchedulingAsync(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableSchedulingAsync (Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableSchedulingAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; disableComputeNodeSchedulingOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.DisableSchedulingAsync(System.Nullable{Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableSchedulingAsync : Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.DisableSchedulingAsync (disableComputeNodeSchedulingOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disableComputeNodeSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="disableComputeNodeSchedulingOption"><span data-ttu-id="ded09-125">Gibt an, was mit den derzeit ausgeführten Tasks.</span><span class="sxs-lookup"><span data-stu-id="ded09-125">Specifies what to do with currently running tasks.</span></span> <span data-ttu-id="ded09-126">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-126">The default is <see cref="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-127">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-127">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-128">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-128">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-129">Deaktiviert die aufgabenplanung auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-129">Disables task scheduling on the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-130">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-130">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="ded09-131">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ded09-131">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScheduling">
      <MemberSignature Language="C#" Value="public void EnableScheduling (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableScheduling(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.EnableScheduling(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableScheduling (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableScheduling : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.EnableScheduling additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-132">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-132">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-133">Ermöglicht die aufgabenplanung auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-133">Enables task scheduling on the compute node.</span></span>
            </summary>
        <remarks><span data-ttu-id="ded09-134">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ded09-134">This is a blocking operation.</span></span> <span data-ttu-id="ded09-135">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.ComputeNode.EnableScheduling(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-135">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.ComputeNode.EnableScheduling(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableSchedulingAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableSchedulingAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.EnableSchedulingAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableSchedulingAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.EnableSchedulingAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-136">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-136">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-137">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-137">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-138">Ermöglicht die aufgabenplanung auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-138">Enables task scheduling on the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-139">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-139">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="ded09-140">Dieser Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ded09-140">This operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration EndpointConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration" Usage="Microsoft.Azure.Batch.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-141">Ruft die Endpunktkonfiguration für die Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="ded09-141">Gets the endpoint configuration for the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt; Errors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Errors As IReadOnlyList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-142">Ruft die Liste von Fehlern, die derzeit von der Computeknoten auftreten.</span><span class="sxs-lookup"><span data-stu-id="ded09-142">Gets the list of errors that are currently being encountered by the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.NodeFile GetNodeFile (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.NodeFile GetNodeFile(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetNodeFile(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeFile (filePath As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As NodeFile" />
      <MemberSignature Language="F#" Value="member this.GetNodeFile : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.NodeFile" Usage="computeNode.GetNodeFile (filePath, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.NodeFile</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="ded09-143">Der Pfad der Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-143">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-144">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-144">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-145">Durch Aufruf zum Abrufen der angegebenen NodeFile blockiert.</span><span class="sxs-lookup"><span data-stu-id="ded09-145">Blocking call to get the specified NodeFile.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-146">Eine Grenze <see cref="T:Microsoft.Azure.Batch.NodeFile" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="ded09-146">A bound <see cref="T:Microsoft.Azure.Batch.NodeFile" /> object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync (string filePath, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; GetNodeFileAsync(string filePath, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetNodeFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeFileAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="computeNode.GetNodeFileAsync (filePath, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filePath"><span data-ttu-id="ded09-147">Der Pfad der Datei abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-147">The path of the file to retrieve.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-148">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-148">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-149">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-149">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-150">Beginnt eine asynchrone Anforderung an den angegebenen NodeFile abrufen.</span><span class="sxs-lookup"><span data-stu-id="ded09-150">Begins an asynchronous request to get the specified NodeFile.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-151">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-151">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFile(System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (rdpStream As Stream, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.GetRDPFile (rdpStream, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rdpStream"><span data-ttu-id="ded09-152">Der Stream, in dem die Daten der RDP-Datei geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-152">The Stream into which the RDP file data will be written.</span></span>  <span data-ttu-id="ded09-153">In diesem Datenstrom werden nicht geschlossen oder durch diesen Aufruf zurückgespult.</span><span class="sxs-lookup"><span data-stu-id="ded09-153">This stream will not be closed or rewound by this call.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-154">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-154">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-155">Blockierenden Aufruf zum Abrufen von RDP Dateidaten für die Compute-Knoten der aktuellen Instanz und dem Schreiben in einen angegebenen Stream.</span><span class="sxs-lookup"><span data-stu-id="ded09-155">Blocking call to get RDP file data targeting the compute node of the current instance and write them to a specified Stream.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFile">
      <MemberSignature Language="C#" Value="public void GetRDPFile (string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void GetRDPFile(string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFile(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub GetRDPFile (rdpFileNameToCreate As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFile : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.GetRDPFile (rdpFileNameToCreate, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rdpFileNameToCreate"><span data-ttu-id="ded09-156">Der Name der RDP-Datei erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-156">The name of the RDP file to be created.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-157">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-157">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-158">Blockierenden Aufruf zum Abrufen von RDP Dateidaten für die Compute-Knoten der aktuellen Instanz und dem Schreiben in eine Datei mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="ded09-158">Blocking call to get RDP file data targeting the compute node of the current instance and write them to a file with the specified name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (System.IO.Stream rdpStream, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(class System.IO.Stream rdpStream, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFileAsync(System.IO.Stream,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : System.IO.Stream * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.GetRDPFileAsync (rdpStream, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpStream" Type="System.IO.Stream" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rdpStream"><span data-ttu-id="ded09-159">Der Stream, in dem die Daten der RDP-Datei geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-159">The Stream into which the RDP file data will be written.</span></span>  <span data-ttu-id="ded09-160">In diesem Datenstrom werden nicht geschlossen oder durch diesen Aufruf zurückgespult.</span><span class="sxs-lookup"><span data-stu-id="ded09-160">This stream will not be closed or rewound by this call.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-161">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-161">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-162">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-162">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-163">Startet einen asynchronen Aufruf zum Abrufen von RDP-Dateidaten für die Compute-Knoten der aktuellen Instanz und dem Schreiben in einen angegebenen Stream.</span><span class="sxs-lookup"><span data-stu-id="ded09-163">Begins an asynchronous call to get RDP file data targeting the compute node of the current instance and write them to a specified Stream.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-164">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-164">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRDPFileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task GetRDPFileAsync (string rdpFileNameToCreate, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task GetRDPFileAsync(string rdpFileNameToCreate, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRDPFileAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRDPFileAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.GetRDPFileAsync (rdpFileNameToCreate, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rdpFileNameToCreate" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rdpFileNameToCreate"><span data-ttu-id="ded09-165">Der Name der RDP-Datei erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="ded09-165">The name of the RDP file to be created.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-166">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-166">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-167">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-167">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-168">Startet einen asynchronen Aufruf zum Abrufen von RDP-Dateidaten für die Compute-Knoten der aktuellen Instanz und dem Schreiben in eine Datei mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="ded09-168">Begins an asynchronous call to get RDP file data targeting the compute node of the current instance and write them to a file with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-169">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-169">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.RemoteLoginSettings GetRemoteLoginSettings(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettings(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRemoteLoginSettings (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As RemoteLoginSettings" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettings : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.RemoteLoginSettings" Usage="computeNode.GetRemoteLoginSettings additionalBehaviors" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.RemoteLoginSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-170">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-170">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-171">Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="ded09-171">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
          <para><span data-ttu-id="ded09-172">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ded09-172">This is a blocking operation.</span></span> <span data-ttu-id="ded09-173">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettingsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-173">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettingsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="ded09-174">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="ded09-174">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="ded09-175">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="ded09-175">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="ded09-176">Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-176">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.RemoteLoginSettings&gt; GetRemoteLoginSettingsAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.GetRemoteLoginSettingsAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetRemoteLoginSettingsAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;" Usage="computeNode.GetRemoteLoginSettingsAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.RemoteLoginSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-177">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-177">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-178">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-178">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-179">Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="ded09-179">Gets the settings required for remote login to a compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-180">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-180">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="ded09-181">Einstellungen für der Abrufvorgang-Remoteanmeldung wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ded09-181">The get remote login settings operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="ded09-182">Diese Methode kann aufgerufen werden, nur dann, wenn der Pool erstellt wurde, mit einem <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="ded09-182">This method can be invoked only if the pool is created with a <see cref="T:Microsoft.Azure.Batch.VirtualMachineConfiguration" /> property.</span></span> <span data-ttu-id="ded09-183">Wenn diese Methode aufgerufen wird, auf mit erstellten Ressourcenpools <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, Batch-Dienst 409 (Konflikt) zurück.</span><span class="sxs-lookup"><span data-stu-id="ded09-183">If this method is invoked on pools created with <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" />, then Batch service returns 409 (Conflict).</span></span> <span data-ttu-id="ded09-184">Für Anwendungspools mit einem <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> -Eigenschaft, eine der Methoden GetRDPFileAsync/GetRDPFile muss verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-184">For pools with a <see cref="T:Microsoft.Azure.Batch.CloudServiceConfiguration" /> property, one of the GetRDPFileAsync/GetRDPFile methods must be used.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Batch.ComputeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-185">Ruft die Compute-Knoten-Id ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-185">Gets the id of compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IPAddress">
      <MemberSignature Language="C#" Value="public string IPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.IPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IPAddress As String" />
      <MemberSignature Language="F#" Value="member this.IPAddress : string" Usage="Microsoft.Azure.Batch.ComputeNode.IPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-186">Ruft die IP-Adresse der Serverknoten zugeordneten ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-186">Gets the IP address associated with the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-187">Ruft ab, ob diese Computeknoten einen dedizierten Knoten ist.</span><span class="sxs-lookup"><span data-stu-id="ded09-187">Gets whether this compute node is a dedicated node.</span></span> <span data-ttu-id="ded09-188">Wenn "false" ist der Knoten eines Knotens mit niedriger Priorität.</span><span class="sxs-lookup"><span data-stu-id="ded09-188">If false, the node is a low-priority node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-189">Ruft den Zeitpunkt, an dem die Serverknoten gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="ded09-189">Gets the time at which the compute node was started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNodeFiles">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles (Nullable&lt;bool&gt; recursive = null, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.NodeFile&gt; ListNodeFiles(valuetype System.Nullable`1&lt;bool&gt; recursive, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.ListNodeFiles(System.Nullable{System.Boolean},Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListNodeFiles : Nullable&lt;bool&gt; * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;" Usage="computeNode.ListNodeFiles (recursive, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.NodeFile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recursive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="recursive"><span data-ttu-id="ded09-190">Bei "true", führt eine rekursive Liste aller Dateien des Knotens.</span><span class="sxs-lookup"><span data-stu-id="ded09-190">If true, performs a recursive list of all files of the node.</span></span> <span data-ttu-id="ded09-191">Wenn "false" gibt nur die Dateien im Stammverzeichnis Knoten zurück.</span><span class="sxs-lookup"><span data-stu-id="ded09-191">If false, returns only the files at the node directory root.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="ded09-192">Steuert die Detailebene der Daten durch einen Aufruf der Azure Batch-Dienst zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ded09-192">Controls the detail level of the data returned by a call to the Azure Batch Service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-193">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt und das Verhalten implementieren die DetailLevel angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-193">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object and after the behavior implementing the DetailLevel.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-194">Stellt synchrone und asynchrone Enumeration von Dateien für den Knoten an.</span><span class="sxs-lookup"><span data-stu-id="ded09-194">Exposes synchronous and asynchronous enumeration of the files for the node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-195">Eine Instanz des IPagedEnumerable, der zum Auflisten von Objekten mit entweder synchronen oder asynchronen Muster verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="ded09-195">An instance of IPagedEnumerable that can be used to enumerate objects using either synchronous or asynchronous patterns.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public void Reboot (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reboot(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Reboot(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reboot (Optional rebootOption As Nullable(Of ComputeNodeRebootOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reboot : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Reboot (rebootOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="rebootOption"><span data-ttu-id="ded09-196">Die Neustart-Option mit dem Neustart verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="ded09-196">The reboot option associated with the reboot.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-197">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-197">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-198">Blockierenden Aufruf Serverknoten neu starten.</span><span class="sxs-lookup"><span data-stu-id="ded09-198">Blocking call to reboot the compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RebootAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RebootAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; rebootOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RebootAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeRebootOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RebootAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RebootAsync (rebootOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeRebootOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="rebootOption"><span data-ttu-id="ded09-199">Die Neustart-Option mit dem Neustart verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="ded09-199">The reboot option associated with the reboot.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-200">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-200">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-201">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-201">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-202">Startet einen asynchronen Aufruf der Serverknoten neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="ded09-202">Begins an asynchronous call to reboot the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-203">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-203">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt; RecentTasks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecentTasks As IReadOnlyList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-204">Ruft die Ausführungsinformationen für die letzten Tasks, die auf diesem Computeknoten ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="ded09-204">Gets the execution information for the most recent tasks that ran on this compute node.</span></span> <span data-ttu-id="ded09-205">Beachten Sie, dass dieses Element nur zurückgegeben wird, wenn mindestens eine Aufgabe auf diesem Computeknoten seit dem Zeitpunkt ausgeführt wurde, die dem aktuellen Pool zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="ded09-205">Note that this element is only returned if at least one task was run on this compute node since the time it was assigned to its current pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="ded09-206">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ded09-206">The detail level for the refresh.</span></span> <span data-ttu-id="ded09-207">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ded09-207">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-208">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-208">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-209">Aktualisiert die <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-209">Refreshes the <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.ComputeNode/&lt;RefreshAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="ded09-210">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ded09-210">The detail level for the refresh.</span></span> <span data-ttu-id="ded09-211">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ded09-211">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.ComputeNode.Id" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-212">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-212">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.ComputeNode.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-213">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-213">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-214">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-214">Refreshes the current <see cref="T:Microsoft.Azure.Batch.ComputeNode" />.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-215">Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-215">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Reimage(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.Reimage(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage (Optional reimageOption As Nullable(Of ComputeNodeReimageOption) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Reimage : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.Reimage (reimageOption, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="reimageOption"><span data-ttu-id="ded09-216">Die reimaging-Option der reimaging zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ded09-216">The reimage option associated with the reimage.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-217">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-217">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-218">Durch Aufruf von reimaging Serverknoten blockiert.</span><span class="sxs-lookup"><span data-stu-id="ded09-218">Blocking call to reimage the compute node.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; reimageOption, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.ReimageAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeReimageOption},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ReimageAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.ReimageAsync (reimageOption, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeReimageOption&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="reimageOption"><span data-ttu-id="ded09-219">Die reimaging-Option der reimaging zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ded09-219">The reimage option associated with the reimage.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-220">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-220">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-221">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-221">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-222">Startet einen asynchronen Aufruf reimaging der Serverknoten an.</span><span class="sxs-lookup"><span data-stu-id="ded09-222">Begins an asynchronous call to reimage the compute node.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-223">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-223">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPool">
      <MemberSignature Language="C#" Value="public void RemoveFromPool (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveFromPool(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RemoveFromPool(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveFromPool (Optional deallocationOption As Nullable(Of ComputeNodeDeallocationOption) = null, Optional resizeTimeout As Nullable(Of TimeSpan) = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPool : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="computeNode.RemoveFromPool (deallocationOption, resizeTimeout, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="deallocationOption">
            <span data-ttu-id="ded09-224">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="ded09-224">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="ded09-225">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-225">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="ded09-226">Die maximale Zeitdauer den der RemoveFromPool-Vorgang ausgeführt werden kann, bevor er von der Azure Batch-System beendet.</span><span class="sxs-lookup"><span data-stu-id="ded09-226">The maximum amount of time which the RemoveFromPool operation can take before being terminated by the Azure Batch system.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-227">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-227">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-228">Blockierenden Aufruf von Compute-Knoten aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="ded09-228">Blocking call to remove the compute node from the pool.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveFromPoolAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveFromPoolAsync (Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption = null, Nullable&lt;TimeSpan&gt; resizeTimeout = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveFromPoolAsync(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; deallocationOption, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; resizeTimeout, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ComputeNode.RemoveFromPoolAsync(System.Nullable{Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveFromPoolAsync : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt; * Nullable&lt;TimeSpan&gt; * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="computeNode.RemoveFromPoolAsync (deallocationOption, resizeTimeout, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deallocationOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption&gt;" />
        <Parameter Name="resizeTimeout" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deallocationOption">
            <span data-ttu-id="ded09-229">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten aus dem Pool entfernt werden können.</span><span class="sxs-lookup"><span data-stu-id="ded09-229">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool.</span></span> <span data-ttu-id="ded09-230">Der Standardwert lautet <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span><span class="sxs-lookup"><span data-stu-id="ded09-230">The default is <see cref="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />.</span></span>
            </param>
        <param name="resizeTimeout"><span data-ttu-id="ded09-231">Die maximale Zeitdauer den der RemoveFromPool-Vorgang ausgeführt werden kann, bevor er von der Azure Batch-System beendet.</span><span class="sxs-lookup"><span data-stu-id="ded09-231">The maximum amount of time which the RemoveFromPool operation can take before being terminated by the Azure Batch system.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ded09-232">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="ded09-232">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ded09-233">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ded09-233">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ded09-234">Startet einen asynchronen Aufruf den Computeknoten aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="ded09-234">Begins an asynchronous call to remove the compute node from the pool.</span></span>
            </summary>
        <returns><span data-ttu-id="ded09-235">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ded09-235">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-236">Ruft die Gesamtanzahl der aktuell ausgeführten Tasks auf den Computeknoten ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-236">Gets the total number of currently running tasks on the compute node.</span></span> <span data-ttu-id="ded09-237">Dies schließt Auftrag Vorbereitung, Auftrags-Version und Auftrags-Manager-Aufgaben, aber nicht für den Pool Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="ded09-237">This includes Job Preparation, Job Release, and Job Manager tasks, but not the pool start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt; SchedulingState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-238">Ruft ab, ob der Knoten für die aufgabenplanung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="ded09-238">Gets whether the node is available for task scheduling.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTask StartTask { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.StartTask" Usage="Microsoft.Azure.Batch.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-239">Ruft die Startaufgabe auf allen Serverknoten in diesem Pool zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ded09-239">Gets the start task associated with all compute nodes in this pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.StartTaskInformation StartTaskInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.StartTaskInformation StartTaskInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StartTaskInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTaskInformation As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInformation : Microsoft.Azure.Batch.StartTaskInformation" Usage="Microsoft.Azure.Batch.ComputeNode.StartTaskInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-240">Ruft die ausführliche Laufzeitinformationen der Startaufgabe, einschließlich der aktuellen Status, Fehlerdetails, Exitcode, Startzeit, Endzeit usw. ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-240">Gets the detailed runtime information of the start task, including current state, error details, exit code, start time, end time, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-241">Ruft den aktuellen Status des Serverknotens ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-241">Gets the current state of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-242">Ruft den Zeitpunkt, zu dem Serverknoten den aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="ded09-242">Gets the time at which the compute node entered the current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-243">Ruft die Anzahl der Aufgaben, die auf diesem Computeknoten, von dem Zeitpunkt, zu den es reserviert wurde dieses Pools ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="ded09-243">Gets the number of tasks that have been run on this compute node from the time it was allocated to this pool.</span></span> <span data-ttu-id="ded09-244">Dies schließt Auftrag Vorbereitung, Auftrags-Version und Auftrags-Manager-Aufgaben, aber nicht für den Pool Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="ded09-244">This includes Job Preparation, Job Release, and Job Manager tasks, but not the pool start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-245">Ruft die Gesamtzahl der Aufgaben, die abgeschlossen (mit ExitCode 0) erfolgreich auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="ded09-245">Gets the total number of tasks which completed successfully (with exitCode 0) on the compute node.</span></span> <span data-ttu-id="ded09-246">Dies schließt Auftrag Vorbereitung, Auftrags-Version und Auftrags-Manager-Aufgaben, aber nicht für den Pool Startaufgabe.</span><span class="sxs-lookup"><span data-stu-id="ded09-246">This includes Job Preparation, Job Release, and Job Manager tasks, but not the pool start task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-247">Die URL der Compute-Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="ded09-247">Gets the URL of compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSize">
      <MemberSignature Language="C#" Value="public string VirtualMachineSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNode.VirtualMachineSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSize As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSize : string" Usage="Microsoft.Azure.Batch.ComputeNode.VirtualMachineSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ded09-248">Ruft die Größe des virtuellen Computers die Compute-Knoten gehostet.</span><span class="sxs-lookup"><span data-stu-id="ded09-248">Gets the size of the virtual machine hosting the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>