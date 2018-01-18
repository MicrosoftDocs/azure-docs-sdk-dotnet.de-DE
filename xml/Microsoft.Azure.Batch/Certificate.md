<Type Name="Certificate" FullName="Microsoft.Azure.Batch.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Batch.IInheritedBehaviors, Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors, class Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Implements IInheritedBehaviors, IRefreshable" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    interface IRefreshable&#xA;    interface ITransportObjectProvider&lt;CertificateAddParameter&gt;&#xA;    interface IInheritedBehaviors&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="ba545-101">Ein Zertifikat, das auf den Serverknoten installiert werden und kann verwendet werden, um Vorgänge auf einem Knoten zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="ba545-101">A certificate that can be installed on compute nodes and can be used to authenticate operations on a node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDelete">
      <MemberSignature Language="C#" Value="public void CancelDelete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDelete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CancelDelete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDelete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDelete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.CancelDelete additionalBehaviors" />
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
        <param name="additionalBehaviors"><span data-ttu-id="ba545-102">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-102">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-103">Bricht einen fehlerhaften Löschvorgang des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-103">Cancels a failed deletion of the certificate.</span></span>  <span data-ttu-id="ba545-104">Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="ba545-104">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="ba545-105">Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="ba545-105">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="ba545-106">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-106">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
          <para><span data-ttu-id="ba545-107">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ba545-107">This is a blocking operation.</span></span> <span data-ttu-id="ba545-108">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-108">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.CancelDeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;CancelDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ba545-109">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-109">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ba545-110">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ba545-110">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-111">Bricht einen fehlerhaften Löschvorgang des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-111">Cancels a failed deletion of the certificate.</span></span>  <span data-ttu-id="ba545-112">Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="ba545-112">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="ba545-113">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ba545-113">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="ba545-114">Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="ba545-114">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="ba545-115">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-115">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="ba545-116">Die "Abbrechen" gelöscht werden asynchron Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="ba545-116">The cancel delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateFormat">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt; CertificateFormat { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateFormat&gt; CertificateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.CertificateFormat" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateFormat As Nullable(Of CertificateFormat)" />
      <MemberSignature Language="F#" Value="member this.CertificateFormat : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt;" Usage="Microsoft.Azure.Batch.Certificate.CertificateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateFormat&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba545-117">Ruft das Format des ausgewählten Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="ba545-117">Gets the format of the certificate data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="public void Commit (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Commit(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Commit(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Commit (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Commit : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Commit additionalBehaviors" />
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
        <param name="additionalBehaviors"><span data-ttu-id="ba545-118">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-118">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-119">Fügt das Zertifikat für das Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="ba545-119">Adds the certificate to the Batch account.</span></span>
            </summary>
        <remarks><span data-ttu-id="ba545-120">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ba545-120">This is a blocking operation.</span></span> <span data-ttu-id="ba545-121">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-121">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CommitAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CommitAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CommitAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.CommitAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CommitAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.CommitAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;CommitAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ba545-122">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-122">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ba545-123">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ba545-123">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-124">Fügt das Zertifikat für das Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="ba545-124">Adds the certificate to the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="ba545-125">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ba545-125">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks><span data-ttu-id="ba545-126">Der Commitvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ba545-126">The commit operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.Certificate.CustomBehaviors" />
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
            <span data-ttu-id="ba545-127">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-127">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="ba545-128">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="ba545-128">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="ba545-129">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="ba545-129">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="ba545-130">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="ba545-130">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Data">
      <MemberSignature Language="C#" Value="public string Data { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Data" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Data" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Data As String" />
      <MemberSignature Language="F#" Value="member this.Data : string" Usage="Microsoft.Azure.Batch.Certificate.Data" />
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
            <span data-ttu-id="ba545-131">Ruft die Rohzertifikatdaten base64-codierte Daten (Inhalte der PFX- oder CER-Datei oder Daten, aus denen die <see cref="T:Microsoft.Azure.Batch.Certificate" /> erstellt wurde).</span><span class="sxs-lookup"><span data-stu-id="ba545-131">Gets the base64-encoded raw certificate data (contents of the .pfx or .cer file or data from which the <see cref="T:Microsoft.Azure.Batch.Certificate" /> was created).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="ba545-132">Diese Eigenschaft wird festgelegt, beim Erstellen eines neuen <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-132">This property is set when creating a new <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span> <span data-ttu-id="ba545-133">Es ist nicht für Zertifikate, die aus der Batch-Dienst abgerufen definiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-133">It is not defined for certificates retrieved from the Batch service.</span></span></para>
          <para><span data-ttu-id="ba545-134">Die maximale Größe beträgt 10 KB.</span><span class="sxs-lookup"><span data-stu-id="ba545-134">The maximum size is 10 KB.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Delete(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Delete(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete (Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.Delete : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Delete additionalBehaviors" />
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
        <param name="additionalBehaviors"><span data-ttu-id="ba545-135">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-135">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-136">Löscht das Zertifikat aus dem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="ba545-136">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="ba545-137">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ba545-137">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="ba545-138">Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="ba545-138">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="ba545-139">Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="ba545-139">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="ba545-140">Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</span><span class="sxs-lookup"><span data-stu-id="ba545-140">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="ba545-141">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba545-141">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="ba545-142">Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</span><span class="sxs-lookup"><span data-stu-id="ba545-142">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="ba545-143">Das Zertifikat ist nicht für alle Pools zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ba545-143">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="ba545-144">Das Zertifikat ist auf den Computeknoten nicht installiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-144">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="ba545-145">(Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</span><span class="sxs-lookup"><span data-stu-id="ba545-145">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="ba545-146">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="ba545-146">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="ba545-147">Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-147">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="ba545-148">Sie können <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="ba545-148">You can use <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="ba545-149">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ba545-149">This is a blocking operation.</span></span> <span data-ttu-id="ba545-150">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-150">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.DeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteAsync : seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.DeleteAsync (additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="additionalBehaviors"><span data-ttu-id="ba545-151">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-151">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ba545-152">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ba545-152">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-153">Löscht das Zertifikat aus dem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="ba545-153">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="ba545-154">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ba545-154">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="ba545-155">Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="ba545-155">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="ba545-156">Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="ba545-156">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="ba545-157">Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</span><span class="sxs-lookup"><span data-stu-id="ba545-157">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="ba545-158">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="ba545-158">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="ba545-159">Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</span><span class="sxs-lookup"><span data-stu-id="ba545-159">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="ba545-160">Das Zertifikat ist nicht für alle Pools zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="ba545-160">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="ba545-161">Das Zertifikat ist auf den Computeknoten nicht installiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-161">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="ba545-162">(Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</span><span class="sxs-lookup"><span data-stu-id="ba545-162">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="ba545-163">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="ba545-163">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="ba545-164">Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-164">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="ba545-165">Sie können <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="ba545-165">You can use <see cref="M:Microsoft.Azure.Batch.Certificate.CancelDeleteAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="ba545-166">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ba545-166">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.DeleteCertificateError DeleteCertificateError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Batch.DeleteCertificateError" Usage="Microsoft.Azure.Batch.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba545-167">Ruft den Fehler, der beim letzten Versuch, dieses Zertifikat löschen aufgetreten sind.</span><span class="sxs-lookup"><span data-stu-id="ba545-167">Gets the error that occurred on the last attempt to delete this certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ba545-168">Diese Eigenschaft ist null, es sei denn, das Zertifikat in der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="ba545-168">This property is null unless the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Password" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string" Usage="Microsoft.Azure.Batch.Certificate.Password" />
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
            <span data-ttu-id="ba545-169">Ruft das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</span><span class="sxs-lookup"><span data-stu-id="ba545-169">Gets the password to access the certificate private key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ba545-170">Diese Eigenschaft wird festgelegt, beim Erstellen eines neuen <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus Daten der PFX-Format (finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" /> und <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />).</span><span class="sxs-lookup"><span data-stu-id="ba545-170">This property is set when creating a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .pfx format data (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" /> and <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />).</span></span> <span data-ttu-id="ba545-171">Es ist nicht für Zertifikate, die aus der Batch-Dienst abgerufen definiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-171">It is not defined for certificates retrieved from the Batch service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt; PreviousState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousState As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;" Usage="Microsoft.Azure.Batch.Certificate.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba545-172">Ruft den vorherigen Zustand des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-172">Gets the previous state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ba545-173">Wenn das Zertifikat in die erste ist <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand befindet, wird die PreviousState-Eigenschaft ist nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-173">If the certificate is in its initial <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state, the PreviousState property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.Certificate.PreviousStateTransitionTime" />
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
            <span data-ttu-id="ba545-174">Ruft den Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="ba545-174">Gets the time at which the certificate entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="ba545-175">Wenn das Zertifikat in die erste ist <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand befindet, wird die PreviousStateTransitionTime-Eigenschaft ist nicht definiert.</span><span class="sxs-lookup"><span data-stu-id="ba545-175">If the certificate is in its initial <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state, the PreviousStateTransitionTime property is not defined.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string" Usage="Microsoft.Azure.Batch.Certificate.PublicData" />
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
            <span data-ttu-id="ba545-176">Ruft den öffentlichen Teil des Zertifikats als eine Zeichenfolge, enthält die Daten der Base64-codierte CER-Format ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-176">Gets the public part of the certificate as a string containing base-64 encoded .cer format data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit&#xA;override this.Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificate.Refresh (detailLevel, additionalBehaviors)" />
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
        <param name="detailLevel"><span data-ttu-id="ba545-177">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ba545-177">The detail level for the refresh.</span></span>  <span data-ttu-id="ba545-178">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> oder <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ba545-178">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> or <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ba545-179">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-179">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-180">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-180">Refreshes the current <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Certificate.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificate.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
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
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Certificate/&lt;RefreshAsync&gt;d__7))</AttributeName>
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
        <param name="detailLevel"><span data-ttu-id="ba545-181">Die Detailstufe für die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ba545-181">The detail level for the refresh.</span></span>  <span data-ttu-id="ba545-182">Wenn einer der weglässt Detailebene der <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> oder <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> -Eigenschaft angegeben ist, scheitert die Aktualisierung.</span><span class="sxs-lookup"><span data-stu-id="ba545-182">If a detail level which omits the <see cref="P:Microsoft.Azure.Batch.Certificate.Thumbprint" /> or <see cref="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" /> property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ba545-183">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-183">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.Certificate.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ba545-184">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ba545-184">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="ba545-185">Aktualisiert das aktuelle <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span><span class="sxs-lookup"><span data-stu-id="ba545-185">Refreshes the current <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="ba545-186">Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Aktualisierungsvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ba545-186">A <see cref="T:System.Threading.Tasks.Task" /> representing the asynchronous refresh operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.CertificateState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;" Usage="Microsoft.Azure.Batch.Certificate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ba545-187">Ruft den aktuellen Status des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-187">Gets the current state of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.Certificate.StateTransitionTime" />
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
            <span data-ttu-id="ba545-188">Ruft den Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.</span><span class="sxs-lookup"><span data-stu-id="ba545-188">Gets the time at which the certificate entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Batch.Certificate.Thumbprint" />
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
            <span data-ttu-id="ba545-189">Ruft den Fingerabdruck des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-189">Gets the thumbprint of the certificate.</span></span> <span data-ttu-id="ba545-190">Dies ist eine Sequenz von bis zu 40 hexadezimale Ziffern.</span><span class="sxs-lookup"><span data-stu-id="ba545-190">This is a sequence of up to 40 hex digits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string" Usage="Microsoft.Azure.Batch.Certificate.ThumbprintAlgorithm" />
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
            <span data-ttu-id="ba545-191">Ruft den Algorithmus, der zum Ableiten des Fingerabdrucks verwendet.</span><span class="sxs-lookup"><span data-stu-id="ba545-191">Gets the algorithm used to derive the thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Certificate.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.Certificate.Url" />
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
            <span data-ttu-id="ba545-192">Ruft die URL des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="ba545-192">Gets the URL of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>