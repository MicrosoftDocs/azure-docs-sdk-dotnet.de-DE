<Type Name="CertificateOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class CertificateOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CertificateOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CertificateOperationsExtensions" />
  <TypeSignature Language="F#" Value="type CertificateOperationsExtensions = class" />
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
            <span data-ttu-id="81665-101">Erweiterungsmethoden für CertificateOperations.</span><span class="sxs-lookup"><span data-stu-id="81665-101">Extension methods for CertificateOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders Add(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Add (operations, certificate, certificateAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-102">The operations group for this extension method.</span></span>
            </param>
        <param name="certificate">
            <span data-ttu-id="81665-103">Das Zertifikat hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="81665-103">The certificate to be added.</span></span>
            </param>
        <param name="certificateAddOptions">
            <span data-ttu-id="81665-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-105">Das angegebene Konto hinzugefügt ein Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="81665-105">Adds a certificate to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter certificate, class Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions certificateAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter,Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter * Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.AddAsync (operations, certificate, certificateAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;AddAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddParameter" />
        <Parameter Name="certificateAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-106">The operations group for this extension method.</span></span>
            </param>
        <param name="certificate">
            <span data-ttu-id="81665-107">Das Zertifikat hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="81665-107">The certificate to be added.</span></span>
            </param>
        <param name="certificateAddOptions">
            <span data-ttu-id="81665-108">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-110">Das angegebene Konto hinzugefügt ein Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="81665-110">Adds a certificate to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletion">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders CancelDeletion(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions)" />
      <MemberSignature Language="F#" Value="static member CancelDeletion : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletion (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-111">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-112">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-112">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-113">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-113">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-114">Der Fingerabdruck des Zertifikats, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="81665-114">The thumbprint of the certificate being deleted.</span></span>
            </param>
        <param name="certificateCancelDeletionOptions">
            <span data-ttu-id="81665-115">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-115">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-116">Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.</span><span class="sxs-lookup"><span data-stu-id="81665-116">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81665-117">Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus.</span><span class="sxs-lookup"><span data-stu-id="81665-117">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="81665-118">Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen.</span><span class="sxs-lookup"><span data-stu-id="81665-118">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="81665-119">Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="81665-119">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="81665-120">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.</span><span class="sxs-lookup"><span data-stu-id="81665-120">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeletionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt; CancelDeletionAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions certificateCancelDeletionOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CancelDeletionAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.CancelDeletionAsync (operations, thumbprintAlgorithm, thumbprint, certificateCancelDeletionOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;CancelDeletionAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateCancelDeletionOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateCancelDeletionOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-121">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-122">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-122">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-123">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-123">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-124">Der Fingerabdruck des Zertifikats, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="81665-124">The thumbprint of the certificate being deleted.</span></span>
            </param>
        <param name="certificateCancelDeletionOptions">
            <span data-ttu-id="81665-125">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-127">Bricht einen fehlerhaften Löschvorgang eines Zertifikats aus dem angegebenen Konto ab.</span><span class="sxs-lookup"><span data-stu-id="81665-127">Cancels a failed deletion of a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81665-128">Wenn Sie versuchen, löschen ein Zertifikat, das von einem Pool verwendet wird oder compute-Knoten, ändert den Status des Zertifikats in DeleteFailed aus.</span><span class="sxs-lookup"><span data-stu-id="81665-128">If you try to delete a certificate that is being used by a pool or compute node, the status of the certificate changes to deleteFailed.</span></span> <span data-ttu-id="81665-129">Wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten, können Sie diesen Vorgang verwenden, um den Status des Zertifikats erneut auf aktiv festzulegen.</span><span class="sxs-lookup"><span data-stu-id="81665-129">If you decide that you want to continue using the certificate, you can use this operation to set the status of the certificate back to active.</span></span> <span data-ttu-id="81665-130">Wenn Sie das Zertifikat löschen möchten, müssen Sie nicht, diesen Vorgang auszuführen, nach dem fehlerhaften Löschvorgang.</span><span class="sxs-lookup"><span data-stu-id="81665-130">If you intend to delete the certificate, you do not need to run this operation after the deletion failed.</span></span> <span data-ttu-id="81665-131">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen.</span><span class="sxs-lookup"><span data-stu-id="81665-131">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Delete (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-132">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-133">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-133">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-134">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-134">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-135">Der Fingerabdruck des Zertifikats, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="81665-135">The thumbprint of the certificate to be deleted.</span></span>
            </param>
        <param name="certificateDeleteOptions">
            <span data-ttu-id="81665-136">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-136">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-137">Löscht ein Zertifikat aus dem angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="81665-137">Deletes a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81665-138">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="81665-138">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="81665-139">Bevor Sie ein Zertifikat löschen können, Sie müssen daher sicherstellen, dass das Zertifikat ist nicht mit vorhandenen Pools verknüpft, das Zertifikat ist nicht installiert, auf den Computeknoten (auch wenn Sie ein Zertifikat aus einem Pool entfernen, es nicht entfernt, wird aus vorhandenen Serverknoten in diesem Pool bis Neustart), und keine ausgeführten Tasks richten sich nach dem Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="81665-139">Before you can delete a certificate, you must therefore make sure that the certificate is not associated with any existing pools, the certificate is not installed on any compute nodes (even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart), and no running tasks depend on the certificate.</span></span> <span data-ttu-id="81665-140">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="81665-140">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="81665-141">Der Zertifikatstatus wechselt zu DeleteFailed.</span><span class="sxs-lookup"><span data-stu-id="81665-141">The certificate status changes to deleteFailed.</span></span> <span data-ttu-id="81665-142">"Abbrechen" Zertifikat löschen können Sie den Status erneut auf aktiv festzulegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="81665-142">You can use Cancel Delete Certificate to set the status back to active if you decide that you want to continue using the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions certificateDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.DeleteAsync (operations, thumbprintAlgorithm, thumbprint, certificateDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-143">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-144">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-144">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-145">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-145">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-146">Der Fingerabdruck des Zertifikats, das gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="81665-146">The thumbprint of the certificate to be deleted.</span></span>
            </param>
        <param name="certificateDeleteOptions">
            <span data-ttu-id="81665-147">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-147">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-149">Löscht ein Zertifikat aus dem angegebenen Konto.</span><span class="sxs-lookup"><span data-stu-id="81665-149">Deletes a certificate from the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="81665-150">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="81665-150">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="81665-151">Bevor Sie ein Zertifikat löschen können, Sie müssen daher sicherstellen, dass das Zertifikat ist nicht mit vorhandenen Pools verknüpft, das Zertifikat ist nicht installiert, auf den Computeknoten (auch wenn Sie ein Zertifikat aus einem Pool entfernen, es nicht entfernt, wird aus vorhandenen Serverknoten in diesem Pool bis Neustart), und keine ausgeführten Tasks richten sich nach dem Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="81665-151">Before you can delete a certificate, you must therefore make sure that the certificate is not associated with any existing pools, the certificate is not installed on any compute nodes (even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart), and no running tasks depend on the certificate.</span></span> <span data-ttu-id="81665-152">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="81665-152">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="81665-153">Der Zertifikatstatus wechselt zu DeleteFailed.</span><span class="sxs-lookup"><span data-stu-id="81665-153">The certificate status changes to deleteFailed.</span></span> <span data-ttu-id="81665-154">"Abbrechen" Zertifikat löschen können Sie den Status erneut auf aktiv festzulegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="81665-154">You can use Cancel Delete Certificate to set the status back to active if you decide that you want to continue using the certificate.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.Certificate Get (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.Certificate Get(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.Certificate" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.Get (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-155">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-156">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-156">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-157">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-157">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-158">Der Fingerabdruck des Zertifikats zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="81665-158">The thumbprint of the certificate to get.</span></span>
            </param>
        <param name="certificateGetOptions">
            <span data-ttu-id="81665-159">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-160">Ruft Informationen über das angegebene Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="81665-160">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions certificateGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.GetAsync (operations, thumbprintAlgorithm, thumbprint, certificateGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="certificateGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-161">The operations group for this extension method.</span></span>
            </param>
        <param name="thumbprintAlgorithm">
            <span data-ttu-id="81665-162">Der Algorithmus verwendet, um den fingerabdruckparameter ableiten.</span><span class="sxs-lookup"><span data-stu-id="81665-162">The algorithm used to derive the thumbprint parameter.</span></span> <span data-ttu-id="81665-163">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="81665-163">This must be sha1.</span></span>
            </param>
        <param name="thumbprint">
            <span data-ttu-id="81665-164">Der Fingerabdruck des Zertifikats zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="81665-164">The thumbprint of the certificate to get.</span></span>
            </param>
        <param name="certificateGetOptions">
            <span data-ttu-id="81665-165">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-165">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-167">Ruft Informationen über das angegebene Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="81665-167">Gets information about the specified certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; List(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.List (operations, certificateListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-168">The operations group for this extension method.</span></span>
            </param>
        <param name="certificateListOptions">
            <span data-ttu-id="81665-169">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-169">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-170">Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="81665-170">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, class Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions certificateListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListAsync (operations, certificateListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="certificateListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-171">The operations group for this extension method.</span></span>
            </param>
        <param name="certificateListOptions">
            <span data-ttu-id="81665-172">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-172">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-174">Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="81665-174">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt; ListNext(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNext (operations, nextPageLink, certificateListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81665-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81665-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="certificateListNextOptions">
            <span data-ttu-id="81665-177">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-177">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-178">Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="81665-178">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.ICertificateOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions certificateListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.ICertificateOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.ICertificateOperations * string * Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions.ListNextAsync (operations, nextPageLink, certificateListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.CertificateOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.Certificate&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.ICertificateOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="certificateListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.CertificateListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="81665-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="81665-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="81665-180">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="81665-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="certificateListNextOptions">
            <span data-ttu-id="81665-181">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="81665-181">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="81665-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="81665-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="81665-183">Listet alle Zertifikate, die dem angegebenen Konto hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="81665-183">Lists all of the certificates that have been added to the specified account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>