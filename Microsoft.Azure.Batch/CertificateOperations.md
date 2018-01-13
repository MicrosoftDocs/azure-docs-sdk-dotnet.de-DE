<Type Name="CertificateOperations" FullName="Microsoft.Azure.Batch.CertificateOperations">
  <TypeSignature Language="C#" Value="public class CertificateOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CertificateOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.CertificateOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class CertificateOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type CertificateOperations = class&#xA;    interface IInheritedBehaviors" />
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
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="a6da7-101">Führt zertifikatbezogene Vorgänge auf Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="a6da7-101">Performs certificate-related operations on an Azure Batch account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancelDeleteCertificate">
      <MemberSignature Language="C#" Value="public void CancelDeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CancelDeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub CancelDeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.CancelDeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
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
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-102">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-102">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-103">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-103">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-104">Der Fingerabdruck des Zertifikats, das konnte nicht gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-104">The thumbprint of the certificate that failed to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-105">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-105">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-106">Bricht einen fehlerhaften Löschvorgang des angegebenen Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="a6da7-106">Cancels a failed deletion of the specified certificate.</span></span>  <span data-ttu-id="a6da7-107">Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="a6da7-107">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-108">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-108">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="a6da7-109">Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="a6da7-109">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="a6da7-110">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-110">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="a6da7-111">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a6da7-111">This is a blocking operation.</span></span> <span data-ttu-id="a6da7-112">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-112">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelDeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CancelDeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CancelDeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CancelDeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.CancelDeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;CancelDeleteCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-113">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-113">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-114">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-114">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-115">Der Fingerabdruck des Zertifikats, das konnte nicht gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-115">The thumbprint of the certificate that failed to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-116">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-116">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6da7-117">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6da7-117">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-118">Bricht einen fehlerhaften Löschvorgang des angegebenen Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="a6da7-118">Cancels a failed deletion of the specified certificate.</span></span>  <span data-ttu-id="a6da7-119">Dies kann erfolgen, wenn das Zertifikat verfügt die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> Status, und stellt das Zertifikat an die <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="a6da7-119">This can be done only when the certificate is in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" /> state, and restores the certificate to the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Active" /> state.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-120">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-120">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="a6da7-121">Wenn Sie weiterhin das Zertifikat (anstelle der Rückgabe an den aktiven) löschen möchten, müssen Sie nicht des fehlerhaften Löschvorgangs "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="a6da7-121">If you still wish to delete the certificate (instead of returning it to Active), you do not need to cancel the failed deletion.</span></span> <span data-ttu-id="a6da7-122">Sie müssen sicherstellen, dass das Zertifikat nicht von Ressourcen verwendet wird, und klicken Sie dann Sie es beim Löschen des Zertifikats versuchen (siehe <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-122">You must make sure that the certificate is not being used by any resources, and then you can try again to delete the certificate (see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="a6da7-123">Die "Abbrechen" gelöscht werden asynchron Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="a6da7-123">The cancel delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] cerRawData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] cerRawData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerRawData As Byte()) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerRawData" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerRawData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="cerRawData"><span data-ttu-id="a6da7-124">Die Zertifikatdaten im CER-Format.</span><span class="sxs-lookup"><span data-stu-id="a6da7-124">The certificate data in .cer format.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-125">Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus Daten der CER-Format im Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="a6da7-125">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .cer format data in memory.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-126">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-126">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string cerFileName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string cerFileName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (cerFileName As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate cerFileName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cerFileName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cerFileName"><span data-ttu-id="a6da7-127">Der Pfad der CER-Datei.</span><span class="sxs-lookup"><span data-stu-id="a6da7-127">The path to the .cer file.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-128">Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus einer CER-Datei.</span><span class="sxs-lookup"><span data-stu-id="a6da7-128">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from a .cer file.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-129">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-129">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (byte[] pfxRawData, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(unsigned int8[] pfxRawData, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.Byte[],System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxRawData As Byte(), password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : byte[] * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxRawData, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxRawData" Type="System.Byte[]" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxRawData"><span data-ttu-id="a6da7-130">Die Zertifikatdaten im PFX-Format.</span><span class="sxs-lookup"><span data-stu-id="a6da7-130">The certificate data in .pfx format.</span></span></param>
        <param name="password"><span data-ttu-id="a6da7-131">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-131">The password to access the certificate private key.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-132">Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus Daten der PFX-Format im Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="a6da7-132">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from .pfx format data in memory.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-133">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-133">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate CreateCertificate (string pfxFileName, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate CreateCertificate(string pfxFileName, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.CreateCertificate(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCertificate (pfxFileName As String, password As String) As Certificate" />
      <MemberSignature Language="F#" Value="member this.CreateCertificate : string * string -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.CreateCertificate (pfxFileName, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFileName" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFileName"><span data-ttu-id="a6da7-134">Der Pfad zur PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="a6da7-134">The path to the .pfx file.</span></span></param>
        <param name="password"><span data-ttu-id="a6da7-135">Das Kennwort für privaten Schlüssel des Zertifikats zugreifen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-135">The password to access the certificate private key.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-136">Erstellt ein neues <see cref="T:Microsoft.Azure.Batch.Certificate" /> aus einer PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="a6da7-136">Creates a new <see cref="T:Microsoft.Azure.Batch.Certificate" /> from a .pfx file.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-137">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> , ein neues Zertifikat, das nicht im Batch-Dienst hinzugefügt wurde darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-137">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> representing a new certificate that has not been added to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />
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
            <span data-ttu-id="a6da7-138">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.CertificateOperations" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-138">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.CertificateOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="a6da7-139">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-139">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="a6da7-140">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="a6da7-140">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="a6da7-141">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="a6da7-141">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificate">
      <MemberSignature Language="C#" Value="public void DeleteCertificate (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteCertificate(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificate(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteCertificate (thumbprintAlgorithm As String, thumbprint As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificate : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="certificateOperations.DeleteCertificate (thumbprintAlgorithm, thumbprint, additionalBehaviors)" />
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
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-142">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-142">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-143">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-143">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-144">Der Fingerabdruck des Zertifikats zu löschen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-144">The thumbprint of the certificate to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-145">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-145">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-146">Löscht das Zertifikat aus dem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="a6da7-146">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="a6da7-147">Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-147">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="a6da7-148">Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="a6da7-148">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="a6da7-149">Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</span><span class="sxs-lookup"><span data-stu-id="a6da7-149">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="a6da7-150">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a6da7-150">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="a6da7-151">Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</span><span class="sxs-lookup"><span data-stu-id="a6da7-151">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="a6da7-152">Das Zertifikat ist nicht für alle Pools zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a6da7-152">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="a6da7-153">Das Zertifikat ist auf den Computeknoten nicht installiert.</span><span class="sxs-lookup"><span data-stu-id="a6da7-153">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="a6da7-154">(Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</span><span class="sxs-lookup"><span data-stu-id="a6da7-154">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="a6da7-155">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="a6da7-155">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="a6da7-156">Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-156">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="a6da7-157">Sie können <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="a6da7-157">You can use <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="a6da7-158">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a6da7-158">This is a blocking operation.</span></span> <span data-ttu-id="a6da7-159">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-159">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCertificateAsync (string thumbprintAlgorithm, string thumbprint, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteCertificateAsync(string thumbprintAlgorithm, string thumbprint, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.DeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateAsync : string * string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="certificateOperations.DeleteCertificateAsync (thumbprintAlgorithm, thumbprint, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;DeleteCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-160">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-160">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-161">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-161">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-162">Der Fingerabdruck des Zertifikats zu löschen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-162">The thumbprint of the certificate to delete.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-163">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-163">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6da7-164">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6da7-164">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-165">Löscht das Zertifikat aus dem Batch-Konto an.</span><span class="sxs-lookup"><span data-stu-id="a6da7-165">Deletes the certificate from the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-166">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-166">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="a6da7-167">Der Löschvorgang fordert an, dass das Zertifikat gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-167">The delete operation requests that the certificate be deleted.</span></span>  <span data-ttu-id="a6da7-168">Die Anforderung wird das Zertifikat abgelegt, der <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="a6da7-168">The request puts the certificate in the <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.Deleting" /> state.</span></span>
            <span data-ttu-id="a6da7-169">Der Batch-Dienst führt das tatsächliches Zertifikat löschen, ohne weitere Aktion des Clients.</span><span class="sxs-lookup"><span data-stu-id="a6da7-169">The Batch service will perform the actual certificate deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="a6da7-170">Ein Zertifikat kann nicht gelöscht werden, wenn eine Ressource (Pool oder Compute-Knoten) verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="a6da7-170">You cannot delete a certificate if a resource (pool or compute node) is using it.</span></span> <span data-ttu-id="a6da7-171">Bevor Sie ein Zertifikat löschen können, müssen Sie daher sicherstellen, dass:</span><span class="sxs-lookup"><span data-stu-id="a6da7-171">Before you can delete a certificate, you must therefore make sure that:</span></span></para>
          <list type="bullet">
            <item>
              <description><span data-ttu-id="a6da7-172">Das Zertifikat ist nicht für alle Pools zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a6da7-172">The certificate is not associated with any pools.</span></span></description>
            </item>
            <item>
              <description><span data-ttu-id="a6da7-173">Das Zertifikat ist auf den Computeknoten nicht installiert.</span><span class="sxs-lookup"><span data-stu-id="a6da7-173">The certificate is not installed on any compute nodes.</span></span>  <span data-ttu-id="a6da7-174">(Auch wenn Sie ein Zertifikat aus einem Pool entfernen, ist es nicht entfernt, von vorhandenen Computeknoten in diesem Pool bis Neustart.)</span><span class="sxs-lookup"><span data-stu-id="a6da7-174">(Even if you remove a certificate from a pool, it is not removed from existing compute nodes in that pool until they restart.)</span></span></description>
            </item>
          </list>
          <para><span data-ttu-id="a6da7-175">Wenn Sie versuchen, ein Zertifikat zu löschen, die verwendet wird, schlägt der Löschvorgang fehl.</span><span class="sxs-lookup"><span data-stu-id="a6da7-175">If you try to delete a certificate that is in use, the deletion fails.</span></span> <span data-ttu-id="a6da7-176">Die statusänderung des Zertifikats zu <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-176">The certificate state changes to <see cref="F:Microsoft.Azure.Batch.Common.CertificateState.DeleteFailed" />.</span></span>
            <span data-ttu-id="a6da7-177">Sie können <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> auf den Status wieder auf aktiv festlegen, wenn Sie sich entscheiden, dass Sie das Zertifikat weiterhin zu verwenden möchten.</span><span class="sxs-lookup"><span data-stu-id="a6da7-177">You can use <see cref="M:Microsoft.Azure.Batch.CertificateOperations.CancelDeleteCertificateAsync(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" /> to set the status back to Active if you decide that you want to continue using the certificate.</span></span></para>
          <para><span data-ttu-id="a6da7-178">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-178">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Certificate GetCertificate (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.Certificate GetCertificate(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificate(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetCertificate : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.Certificate" Usage="certificateOperations.GetCertificate (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Certificate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-179">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-179">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-180">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-180">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-181">Der Fingerabdruck des Zertifikats zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="a6da7-181">The thumbprint of the certificate to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="a6da7-182">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-182">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-183">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-183">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-184">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.Certificate" /> ab.</span><span class="sxs-lookup"><span data-stu-id="a6da7-184">Gets the specified <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-185">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> mit Informationen über das angegebene Zertifikat in das Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="a6da7-185">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> containing information about the specified certificate in the Azure Batch account.</span></span></returns>
        <remarks><span data-ttu-id="a6da7-186">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="a6da7-186">This is a blocking operation.</span></span> <span data-ttu-id="a6da7-187">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-187">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync (string thumbprintAlgorithm, string thumbprint, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Certificate&gt; GetCertificateAsync(string thumbprintAlgorithm, string thumbprint, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.GetCertificateAsync(System.String,System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetCertificateAsync : string * string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.GetCertificateAsync (thumbprintAlgorithm, thumbprint, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.CertificateOperations/&lt;GetCertificateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="thumbprintAlgorithm"><span data-ttu-id="a6da7-188">Der Algorithmus zum Ableiten der <paramref name="thumbprint" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="a6da7-188">The algorithm used to derive the <paramref name="thumbprint" /> parameter.</span></span> <span data-ttu-id="a6da7-189">Diese Angabe muss sha1.</span><span class="sxs-lookup"><span data-stu-id="a6da7-189">This must be sha1.</span></span></param>
        <param name="thumbprint"><span data-ttu-id="a6da7-190">Der Fingerabdruck des Zertifikats zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="a6da7-190">The thumbprint of the certificate to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="a6da7-191">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-191">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-192">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-192">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="a6da7-193">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="a6da7-193">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-194">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.Certificate" /> ab.</span><span class="sxs-lookup"><span data-stu-id="a6da7-194">Gets the specified <see cref="T:Microsoft.Azure.Batch.Certificate" />.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-195">Ein <see cref="T:Microsoft.Azure.Batch.Certificate" /> mit Informationen über das angegebene Zertifikat in das Azure Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="a6da7-195">A <see cref="T:Microsoft.Azure.Batch.Certificate" /> containing information about the specified certificate in the Azure Batch account.</span></span></returns>
        <remarks><span data-ttu-id="a6da7-196">Der Abrufvorgang für das Zertifikat wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a6da7-196">The get certificate operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCertificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt; ListCertificates (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.Certificate&gt; ListCertificates(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.CertificateOperations.ListCertificates(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListCertificates : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;" Usage="certificateOperations.ListCertificates (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.Certificate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="a6da7-197">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="a6da7-197">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="a6da7-198">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="a6da7-198">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.CertificateOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="a6da7-199">Listet die <see cref="T:Microsoft.Azure.Batch.Certificate">Zertifikate</see> in dem Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="a6da7-199">Enumerates the <see cref="T:Microsoft.Azure.Batch.Certificate">certificates</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="a6da7-200">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die Zertifikate aufgelistet werden, synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="a6da7-200">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate certificates asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="a6da7-201">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Zertifikate aus dem Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-201">This method returns immediately; the certificates are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="a6da7-202">Datenabruf ist nicht atomaren; Zertifikate werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a6da7-202">Retrieval is non-atomic; certificates are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>