<Type Name="FabricClient+ApplicationManagementClient" FullName="System.Fabric.FabricClient+ApplicationManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ApplicationManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ApplicationManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ApplicationManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="9e2ef-101">Stellt die Funktionalität zum Verwalten von Service Fabric-Anwendungen bereit.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-101">Provides the functionality to manage Service Fabric applications.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="9e2ef-102">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-102">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="9e2ef-103">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-103">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="9e2ef-104">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-104">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="9e2ef-105">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-105">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="9e2ef-106">Der vollständige Pfad für das Anwendungspaket für die Quelle.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-106">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-107">Der relative Pfad für das Ziel in den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-107">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="9e2ef-108">Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-108">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-109">Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-109">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="9e2ef-110">Das Timeout des Vorgangs wird standardmäßig auf 30 Minuten für systemeigenes Image Store, und es ist kein Timeout-Kapazität für XStore und Dateifreigabe.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-110">The timeout of the operation will default to 30 minutes for native image store and there is no timeout capacity for XStore and file share.</span></span> <span data-ttu-id="9e2ef-111">Kann auch sollten Sie richtige Timeoutwert angeben, in der Funktion überladen von Operatoren<see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></span><span class="sxs-lookup"><span data-stu-id="9e2ef-111">Can also consider specifying proper timeout value in the overloading function <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" /></span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-112">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-112">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-113">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-113">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-114">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-114">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-115">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-115">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-117">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-117">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-118">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-118">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="9e2ef-119">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-119">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="9e2ef-120">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-120">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="9e2ef-121">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-121">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="9e2ef-122">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-122">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="9e2ef-123">Der vollständige Pfad für das Anwendungspaket für die Quelle.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-123">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-124">Der relative Pfad für das Ziel in den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-124">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="9e2ef-125">Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-125">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-126">Das Timeout der Anwendung Paket Kopiervorgang</span><span class="sxs-lookup"><span data-stu-id="9e2ef-126">The timeout of copying application package operation</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-127">Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-127">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-128">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-128">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-129">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-129">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-130">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-130">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-131">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-131">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-132"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-132"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-133">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-133">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-134">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-134">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyApplicationPackage">
      <MemberSignature Language="C#" Value="public void CopyApplicationPackage (string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, System.Fabric.IImageStoreProgressHandler progressHandler, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyApplicationPackage(string imageStoreConnectionString, string applicationPackagePath, string applicationPackagePathInImageStore, class System.Fabric.IImageStoreProgressHandler progressHandler, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.Fabric.IImageStoreProgressHandler,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyApplicationPackage (imageStoreConnectionString As String, applicationPackagePath As String, applicationPackagePathInImageStore As String, progressHandler As IImageStoreProgressHandler, timeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.CopyApplicationPackage : string * string * string * System.Fabric.IImageStoreProgressHandler * TimeSpan -&gt; unit" Usage="applicationManagementClient.CopyApplicationPackage (imageStoreConnectionString, applicationPackagePath, applicationPackagePathInImageStore, progressHandler, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="applicationPackagePath" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="progressHandler" Type="System.Fabric.IImageStoreProgressHandler" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="9e2ef-135">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-135">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="9e2ef-136">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-136">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="9e2ef-137">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-137">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="9e2ef-138">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-138">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePath">
          <para><span data-ttu-id="9e2ef-139">Der vollständige Pfad für das Anwendungspaket für die Quelle.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-139">The full path to the source application package.</span></span></para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-140">Der relative Pfad für das Ziel in den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-140">The relative path for the destination in the Image Store.</span></span> <span data-ttu-id="9e2ef-141">Dieser Pfad ist relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Anwendung Paket kopieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-141">This path is created relative to the root directory in the image store and used as the destination for the application package copy.</span></span></para>
        </param>
        <param name="progressHandler">
          <para><span data-ttu-id="9e2ef-142">Der Status-Handler zum Abrufen von Statusinformationen Echtzeit</span><span class="sxs-lookup"><span data-stu-id="9e2ef-142">The progress handler to retrieve real time progress information</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-143">Das Timeout der Anwendung Paket Kopiervorgang</span><span class="sxs-lookup"><span data-stu-id="9e2ef-143">The timeout of copying application package operation</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-144">Lädt ein Anwendungspaket in den Imagespeicher besitzen als Vorbereitung für die Bereitstellung eines neuen Anwendungstyp hoch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-144">Uploads an application package to the Image Store in preparation for provisioning a new application type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-145">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-145">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-146">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-146">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-147">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-147">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-148">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-148">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-149"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-149"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-150">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-150">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-151">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-151">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync applicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para><span data-ttu-id="9e2ef-152">Die Beschreibung der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-152">The description of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-153">Erstellt und die jeweilige Service Fabric-Anwendung instanziiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-153">Creates and instantiates the specific Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-154">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-154">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-155">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-155">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-156">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-156">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-157"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-157"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-158"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-159"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-159"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-161"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: Der angeforderte Anwendungstyp wurde noch nicht bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-161"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: The requested application type has not been provisioned yet.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-162">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-162">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-163">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-163">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-164">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-164">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-165">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-165">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="9e2ef-166"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-166"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-167">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-167">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-168">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-168">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="9e2ef-169">Die angegebene Kapazität Anwendungsparameter sind falsch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-169">The application capacity parameters specified are incorrect.</span></span> <span data-ttu-id="9e2ef-170">Verweisen auf <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-170">Refer to <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateApplicationAsync (System.Fabric.Description.ApplicationDescription applicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateApplicationAsync(class System.Fabric.Description.ApplicationDescription applicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.CreateApplicationAsync(System.Fabric.Description.ApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateApplicationAsync : System.Fabric.Description.ApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.CreateApplicationAsync (applicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationDescription" Type="System.Fabric.Description.ApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationDescription">
          <para><span data-ttu-id="9e2ef-171">Die Beschreibung der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-171">The description of the application.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-172">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-172">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-173">Das CancellationToken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-173">The CancellationToken that the operation is observing.</span></span> <span data-ttu-id="9e2ef-174">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-174">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-175">Erstellt und die jeweilige Service Fabric-Anwendung instanziiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-175">Creates and instantiates the specific Service Fabric application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-176">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-176">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-177">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-177">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-178">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-178">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-179"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-179"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-180"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-180"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-181"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf dem ImageStore gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-181"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the ImageStore.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-183"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: Der angeforderte Anwendungstyp wurde noch nicht bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-183"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound" />: The requested application type has not been provisioned yet.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-184">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-184">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-185">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-185">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-186">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-186">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-187">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-187">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="9e2ef-188"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-188"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-189">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-189">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-190">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-190">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="9e2ef-191">Die angegebene Kapazität Anwendungsparameter sind falsch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-191">The application capacity parameters specified are incorrect.</span></span> <span data-ttu-id="9e2ef-192">Verweisen auf <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-192">Refer to <see cref="P:System.Fabric.Description.ApplicationDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync deleteApplicationDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para><span data-ttu-id="9e2ef-193">Die Beschreibung der Anwendung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-193">The description of the application to be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-194">Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-194">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-195">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-195">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-196">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-196">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
          <para><span data-ttu-id="9e2ef-197">Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-197">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-198">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-198">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-199">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-199">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-200"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-200"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-201"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-201"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-202">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-202">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-203">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-203">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteApplicationAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-204">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-204">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-205">Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-205">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-206">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-206">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-207">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-207">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-208">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-208">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-209">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-209">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-210"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-210"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-211"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-211"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-212">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-212">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-213">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-213">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Fabric.Description.DeleteApplicationDescription deleteApplicationDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Fabric.Description.DeleteApplicationDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : System.Fabric.Description.DeleteApplicationDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (deleteApplicationDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteApplicationDescription" Type="System.Fabric.Description.DeleteApplicationDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteApplicationDescription">
          <para><span data-ttu-id="9e2ef-214">Die Beschreibung der Anwendung gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-214">The description of the application to be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-215">Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-215">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-216">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-216">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-217">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-217">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-218">Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-218">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-219">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-219">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-220">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-220">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
          <para><span data-ttu-id="9e2ef-221">Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-221">A forceful deletion call can convert on-going normal deletion to forceful one.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-222">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-222">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-223">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-223">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-224"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-224"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-225"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-225"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-226">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-226">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-227">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-227">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteApplicationAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteApplicationAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeleteApplicationAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteApplicationAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeleteApplicationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This api is deprecated, use overload taking DeleteApplicationDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-228">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-228">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-229">Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-229">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-230">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-230">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-231">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-231">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-232">Löscht die Anwendungsinstanz aus dem Cluster, und löscht alle Dienste, die an die Anwendung gehören.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-232">Deletes the application instance from the cluster and deletes all services belonging to the application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-233">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-233">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-234">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-234">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-235">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-235">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-236">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-236">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-237"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-237"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-238"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-238"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-239">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-239">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-240">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-240">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeployServicePackageToNode">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeployServicePackageToNode (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeployServicePackageToNode(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, class System.Fabric.PackageSharingPolicyList sharingPolicies, string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.DeployServicePackageToNode(System.String,System.String,System.String,System.Fabric.PackageSharingPolicyList,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeployServicePackageToNode : string * string * string * System.Fabric.PackageSharingPolicyList * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.DeployServicePackageToNode (applicationTypeName, applicationTypeVersion, serviceManifestName, sharingPolicies, nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="sharingPolicies" Type="System.Fabric.PackageSharingPolicyList" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="9e2ef-241">ApplicationTypeName zugeordneten Dienstmanifest heruntergeladen werden</span><span class="sxs-lookup"><span data-stu-id="9e2ef-241">ApplicationTypeName associated with service manifest to be downloaded</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="9e2ef-242">Version des Anwendungstyp für</span><span class="sxs-lookup"><span data-stu-id="9e2ef-242">Version of ApplicationType</span></span> </para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="9e2ef-243">Name des dienstmanifests, deren Pakete heruntergeladen werden müssen</span><span class="sxs-lookup"><span data-stu-id="9e2ef-243">Name of service manifest whose packages need to be downloaded</span></span></para>
        </param>
        <param name="sharingPolicies">
          <para><span data-ttu-id="9e2ef-244">Freigaberichtlinie für Pakete, die für freigegebene Ordner kopiert werden müssen, die darstellt</span><span class="sxs-lookup"><span data-stu-id="9e2ef-244">Sharing policy representing packages that need to be copied to shared folders</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="9e2ef-245">Der Name des Knotens, in denen Pakete heruntergeladen werden müssen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-245">Name of the node where packages need to be downloaded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-246">Die maximale Zeitdauer lässt das System diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe: System.TimeoutException</span><span class="sxs-lookup"><span data-stu-id="9e2ef-246">The maximum amount of time the system will allow this operation to continue before returning T:System.TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-247">Die <see cref="T:System.Threading.CancellationToken" />, die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-247">The <see cref="T:System.Threading.CancellationToken" />that the operation is observing.</span></span> <span data-ttu-id="9e2ef-248">Sie kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll</span><span class="sxs-lookup"><span data-stu-id="9e2ef-248">It can be used to propagate notification that the operation should be canceled</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-249">Downloads Pakete Dienstmanifest zum Imagecache auf den angegebenen Knoten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-249">Downloads packages associated with service manifest to image cache on specified node.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-250">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-250">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationManifestAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="9e2ef-251">Der Typname wie im Anwendungsmanifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-251">The type name as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="9e2ef-252">Die Version entsprechend den Angaben im Anwendungsmanifest.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-252">The type version as specified in the Application Manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-253">Ruft den Inhalt von einem bereitgestellten Anwendungsmanifest im Cluster gespeichert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-253">Gets the contents of a provisioned Application Manifest stored in the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-254">Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den unformatierten XML-Zeichenfolgeninhalt des Anwendungsmanifests.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-254">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the raw XML string contents of the Application Manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para><span data-ttu-id="9e2ef-255">Die angeforderte Anwendungstyp und-Version wurde nicht bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-255">The requested application type and version has not been provisioned.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetApplicationManifestAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetApplicationManifestAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationManifestAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationManifestAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="applicationManagementClient.GetApplicationManifestAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="9e2ef-256">Der Typname wie im Anwendungsmanifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-256">The type name as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="9e2ef-257">Die Version entsprechend den Angaben im Anwendungsmanifest.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-257">The type version as specified in the Application Manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-258">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-258">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-259">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-259">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-260">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-260">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-261">Ruft den Inhalt von einem bereitgestellten Anwendungsmanifest im Cluster gespeichert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-261">Gets the contents of a provisioned Application Manifest stored in the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-262">Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den unformatierten XML-Zeichenfolgeninhalt des Anwendungsmanifests.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-262">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the raw XML string contents of the Application Manifest.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="F:System.Fabric.FabricErrorCode.ApplicationTypeNotFound">
          <para><span data-ttu-id="9e2ef-263">Die angeforderte Anwendungstyp und-Version wurde nicht bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-263">The requested application type and version has not been provisioned.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationUpgradeProgressAsync (applicationName As Uri) As Task(Of ApplicationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-264">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-264">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-265">Ruft den upgradeverlauf des zur angegebenen Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-265">Retrieves the upgrade progress of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-266">Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den upgradeverlauf des angegebenen Anwendungsinstanz.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-266">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the upgrade progress of the specified application instance.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-267">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-267">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-268">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-268">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-269"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-269"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-270">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-270">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-271">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-271">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ApplicationUpgradeProgress&gt; GetApplicationUpgradeProgressAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.GetApplicationUpgradeProgressAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationUpgradeProgressAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;" Usage="applicationManagementClient.GetApplicationUpgradeProgressAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ApplicationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-272">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-272">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-273">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-273">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-274">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-274">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-275">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-275">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-276">Ruft den upgradeverlauf des zur angegebenen Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-276">Retrieves the upgrade progress of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-277">Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht den upgradeverlauf des angegebenen Anwendungsinstanz.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-277">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the upgrade progress of the specified application instance.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-278">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-278">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-279">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-279">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-280"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-280"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-281">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-281">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-282">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-282">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextApplicationUpgradeDomainAsync (upgradeProgress As ApplicationUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para><span data-ttu-id="9e2ef-283">– Der Verlauf des Upgrades der Anwendungsinstanz von Interesse sind.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-283">–The Upgrade progress of the application instance of interest.</span></span> <span data-ttu-id="9e2ef-284">Dies bietet Informationen über die nächste upgradedomäne aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-284">This provides information about the next upgrade domain to be upgraded.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-285">Weist die Service Fabric Anwendungsinstanz in die nächste upgradedomäne aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-285">Instructs the Service Fabric to upgrade the application instance in the next upgrade domain.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-286">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-286">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-287">Service Fabric würde nur auf die nächste upgradedomäne verschieben, wenn er die upgradedomäne abgeschlossen wurde, die sie zurzeit aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-287">Service Fabric would only move to the next upgrade domain if it has completed the upgrade domain it is currently updating.</span></span> <span data-ttu-id="9e2ef-288">Das heißt, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> Eigenschaft sollte sein ausstehender vor dem Aufrufen dieser Methode.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-288">In other words, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> property should be Pending before calling this method.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-289">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-289">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-290">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-290">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-291"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-291"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-292">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-292">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-293">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-293">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextApplicationUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync (System.Fabric.ApplicationUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextApplicationUpgradeDomainAsync(class System.Fabric.ApplicationUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextApplicationUpgradeDomainAsync : System.Fabric.ApplicationUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.MoveNextApplicationUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para><span data-ttu-id="9e2ef-294">Der Verlauf des Upgrades der Anwendungsinstanz von Interesse sind.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-294">The upgrade progress of the application instance of interest.</span></span> <span data-ttu-id="9e2ef-295">Dies bietet Informationen über die nächste upgradedomäne aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-295">This provides information about the next upgrade domain to be upgraded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-296">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-296">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-297">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-297">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-298">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-298">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-299">Weist das Upgrade mit der Anwendungsinstanz in der nächsten upgradedomäne fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-299">Instructs the upgrade to continue with the application instance in the next upgrade domain.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-300">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-300">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-301">Service Fabric würde nur auf die nächste upgradedomäne verschieben, wenn er die upgradedomäne abgeschlossen wurde, die sie zurzeit aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-301">Service Fabric would only move to the next upgrade domain if it has completed the upgrade domain it is currently updating.</span></span> <span data-ttu-id="9e2ef-302">Das heißt, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> Eigenschaft sollte sein ausstehender vor dem Aufrufen dieser Methode.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-302">In other words, <see cref="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" /> property should be Pending before calling this method.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-303">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-303">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-304">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-304">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-305"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-305"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-306">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-306">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-307">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-307">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (description As ProvisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="9e2ef-308">Beschreibung für die Anforderung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-308">Description of the of provision request.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-309">Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-309">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-310">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-310">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-311">Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-311">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-312">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-312">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-313">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-313">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-314"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-314"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-315"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</span><span class="sxs-lookup"><span data-stu-id="9e2ef-315"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-316">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-316">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-317">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-317">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-318">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-318">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-319">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-319">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-320">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-320">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-321">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-321">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionApplicationAsync (applicationPackagePathInImageStore As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync applicationPackagePathInImageStore" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-322">Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-322">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-323">Stellt einen Service Fabric-Anwendungstyp mit dem Cluster bereit oder registriert einen Service Fabric-Anwendungstyp mit dem Cluster.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-323">Provisions or registers a Service Fabric application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-324">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-324">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-325">Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-325">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-326">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-326">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-327">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-327">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-328"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-328"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-329"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</span><span class="sxs-lookup"><span data-stu-id="9e2ef-329"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-330">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-330">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-331">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-331">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-332">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-332">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-333">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-333">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-334">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-334">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-335">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-335">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (System.Fabric.Description.ProvisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(class System.Fabric.Description.ProvisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.Fabric.Description.ProvisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : System.Fabric.Description.ProvisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ProvisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="9e2ef-336">Beschreibung für die Anforderung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-336">Description of the of provision request.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-337">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-337">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-338">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-338">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-339">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-339">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-340">Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-340">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-341">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-341">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-342">Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-342">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-343">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-343">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-344">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-344">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-345"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-345"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-346"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</span><span class="sxs-lookup"><span data-stu-id="9e2ef-346"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-347">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-347">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-348">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-348">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-349">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-349">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-350">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-350">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-351">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-351">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-352">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-352">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionApplicationAsync (string applicationPackagePathInImageStore, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionApplicationAsync(string applicationPackagePathInImageStore, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.ProvisionApplicationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionApplicationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.ProvisionApplicationAsync (applicationPackagePathInImageStore, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-353">Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-353">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-354">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-354">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-355">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-355">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-356">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-356">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-357">Bereitstellen oder einen Anwendungstyp mit dem Cluster zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-357">Provision or register an application type with the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-358">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-358">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-359">Dies ist obligatorisch, bevor eine Instanz der Anwendung erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-359">This is mandatory before an application instance can be created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-360">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-360">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-361">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-361">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-362"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-362"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="9e2ef-363"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: Der Anwendungstyp wurde bereits bereitgestellt wurde</span><span class="sxs-lookup"><span data-stu-id="9e2ef-363"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeAlreadyExists" />: The application type has already been provisioned</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-364">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-364">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-365">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-365">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-366">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-366">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-367">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-367">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-368">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-368">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-369">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-369">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveApplicationPackage">
      <MemberSignature Language="C#" Value="public void RemoveApplicationPackage (string imageStoreConnectionString, string applicationPackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveApplicationPackage(string imageStoreConnectionString, string applicationPackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RemoveApplicationPackage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveApplicationPackage (imageStoreConnectionString As String, applicationPackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveApplicationPackage : string * string -&gt; unit" Usage="applicationManagementClient.RemoveApplicationPackage (imageStoreConnectionString, applicationPackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="applicationPackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="9e2ef-370">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-370">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="9e2ef-371">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-371">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="9e2ef-372">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-372">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="9e2ef-373">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-373">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="applicationPackagePathInImageStore">
          <para><span data-ttu-id="9e2ef-374">Der relative Pfad für das Anwendungspaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-374">The relative path for the application package in the image store specified during <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.CopyApplicationPackage(System.String,System.String,System.String,System.TimeSpan)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-375">Löscht ein Anwendungspaket aus den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-375">Deletes an application package from the Image Store.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-376">Fehler bei der Zugriff auf eine Datei auf dem ImageStore.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-376">There was an error accessing a file on the ImageStore.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-377"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-377"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-378">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-378">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackApplicationUpgradeAsync (applicationName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-379">Der Name der Anwendung</span><span class="sxs-lookup"><span data-stu-id="9e2ef-379">Name of the application</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-380">Startet die Aktualisierung der aktuellen Anwendung wird ein Rollback ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-380">Starts rolling back the current application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-381">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-381">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-382"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Upgrade für die angegebene Anwendung, ein Rollback aus.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-382"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending upgrade for the specified application to rollback.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RollbackApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackApplicationUpgradeAsync (Uri applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackApplicationUpgradeAsync(class System.Uri applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.RollbackApplicationUpgradeAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackApplicationUpgradeAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.RollbackApplicationUpgradeAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="9e2ef-383">Der Name der Anwendung</span><span class="sxs-lookup"><span data-stu-id="9e2ef-383">Name of the application</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-384">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-384">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-385">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-385">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-386">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-386">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-387">Startet die Aktualisierung der aktuellen Anwendung ein Rollback</span><span class="sxs-lookup"><span data-stu-id="9e2ef-387">Starts rolling back the current application upgrade</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-388">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-388">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (description As UnprovisionApplicationTypeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="9e2ef-389">Beschreibt die Parameter für den Vorgang für das Aufheben der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-389">Describes parameters for the unprovision operation.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-390">Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-390">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-391">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-391">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-392">Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-392">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="9e2ef-393">Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-393">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-394">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-394">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-395">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-395">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-396"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-396"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-397"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-397"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-398">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-398">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-399">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-399">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionApplicationAsync (applicationTypeName As String, applicationTypeVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="9e2ef-400">Der Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-400">The name of the application type.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="9e2ef-401">Die Version des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-401">The version of the application type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-402">Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-402">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-403">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-403">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-404">Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-404">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="9e2ef-405">Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-405">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-406">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-406">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-407">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-407">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-408"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-408"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-409"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-409"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-410">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-410">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-411">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-411">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (System.Fabric.Description.UnprovisionApplicationTypeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(class System.Fabric.Description.UnprovisionApplicationTypeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.Fabric.Description.UnprovisionApplicationTypeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : System.Fabric.Description.UnprovisionApplicationTypeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.UnprovisionApplicationTypeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para><span data-ttu-id="9e2ef-412">Beschreibt die Parameter für den Vorgang für das Aufheben der Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-412">Describes parameters for the unprovision operation.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-413">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-413">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-414">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-414">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-415">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-415">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-416">Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-416">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-417">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-417">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-418">Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-418">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="9e2ef-419">Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-419">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-420">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-420">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-421">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-421">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-422"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-422"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-423"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-423"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-424">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-424">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-425">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-425">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionApplicationAsync (string applicationTypeName, string applicationTypeVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionApplicationAsync(string applicationTypeName, string applicationTypeVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UnprovisionApplicationAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionApplicationAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UnprovisionApplicationAsync (applicationTypeName, applicationTypeVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="9e2ef-426">Der Name des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-426">The name of the application type.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="9e2ef-427">Die Version des Anwendungstyps.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-427">The version of the application type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-428">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-428">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-429">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-429">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="9e2ef-430">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-430">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-431">Hebt die Registrierung und einen Service Fabric-Anwendungstyp aus dem Cluster entfernt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-431">Unregisters and removes a Service Fabric application type from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-432">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-432">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="9e2ef-433">Diese Methode kann nur aufgerufen werden, wenn alle Anwendungsinstanz des Anwendungstyps gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-433">This method can only be called if all application instance of the application type has been deleted.</span></span> <span data-ttu-id="9e2ef-434">Sobald die Registrierung des Anwendungstyps aufgehoben ist, kann keine neue Anwendungsinstanz mehr für diesen bestimmten Anwendungstyp erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-434">Once the application type is unregistered, no new application instance can be created for this particular application type.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-435">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-435">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-436">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-436">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-437"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: Die Anwendung vom Typ wird von einer oder mehreren Anwendungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-437"><see cref="F:System.Fabric.FabricErrorCode.ApplicationTypeInUse" />: The application type is being used by one or more applications.</span></span> </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-438"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-438"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-439">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-439">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-440">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-440">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync applicationUpdateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription"><span data-ttu-id="9e2ef-441">Beschreibung der Anwendung aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-441">Application update description.</span></span></param>
        <summary>
            <span data-ttu-id="9e2ef-442">Eine Service Fabric-Anwendung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-442">Updates a Service Fabric application.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-443">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-443">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-445"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-445"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-446"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Eine andere Anwendungsupdate wird bereits ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-446"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Another application update is already in progress.</span></span>
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="9e2ef-447">Die Anwendung aktualisieren von Parametern angegeben sind falsch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-447">The application update parameters specified are incorrect.</span></span> <span data-ttu-id="9e2ef-448">Verweisen auf <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-448">Refer to <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
          <para>
                <span data-ttu-id="9e2ef-449">Es ist möglich, diese Parameter in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> gültig sind, aber in Kombination mit vorhandenen Anwendungsparameter Kapazität erzeugen sie eine ungültige Kombination.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-449">It is possible that parameters in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> are valid, but when combined with existing application capacity parameters they produce an invalid combination.</span></span> <span data-ttu-id="9e2ef-450">Z. B. <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> auf einen Wert, der höher als die, die im angegebenen <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> wann die Anwendung erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-450">For example, setting <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> to a value that is higher than the one that was specified in <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> when application was created.</span></span>
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationAsync (System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationAsync(class System.Fabric.Description.ApplicationUpdateDescription applicationUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationAsync(System.Fabric.Description.ApplicationUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationAsync : System.Fabric.Description.ApplicationUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationAsync (applicationUpdateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationUpdateDescription" Type="System.Fabric.Description.ApplicationUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationUpdateDescription"><span data-ttu-id="9e2ef-451">Beschreibung der Anwendung aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-451">Application update description.</span></span></param>
        <param name="timeout"><span data-ttu-id="9e2ef-452">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-452">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="9e2ef-453">Das CancellationToken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-453">The CancellationToken that the operation is observing.</span></span>
            <span data-ttu-id="9e2ef-454">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-454">It can be used to propagate notification that the operation should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="9e2ef-455">Eine Service Fabric-Anwendung aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-455">Updates a Service Fabric application.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-456">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-456">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-457"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-457"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-458"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-458"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span>
                </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-459"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Eine andere Anwendungsupdate wird bereits ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-459"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpdateInProgress" />: Another application update is already in progress.</span></span>
                </para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="9e2ef-460">Die Anwendung aktualisieren von Parametern angegeben sind falsch.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-460">The application update parameters specified are incorrect.</span></span> <span data-ttu-id="9e2ef-461">Verweisen auf <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> und <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> für die korrekte Angabe der Kapazität Anwendungsparameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-461">Refer to <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" />, <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MaximumNodes" /> and <see cref="F:System.Fabric.Description.ApplicationUpdateDescription.Metrics" /> for correct specification of application capacity parameters.</span></span>
                </para>
          <para>
                <span data-ttu-id="9e2ef-462">Es ist möglich, diese Parameter in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> gültig sind, aber in Kombination mit vorhandenen Anwendungsparameter Kapazität erzeugen sie eine ungültige Kombination.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-462">It is possible that parameters in <see cref="T:System.Fabric.Description.ApplicationUpdateDescription" /> are valid, but when combined with existing application capacity parameters they produce an invalid combination.</span></span> <span data-ttu-id="9e2ef-463">Z. B. <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> auf einen Wert, der höher als die, die im angegebenen <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> wann die Anwendung erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-463">For example, setting <see cref="P:System.Fabric.Description.ApplicationUpdateDescription.MinimumNodes" /> to a value that is higher than the one that was specified in <see cref="P:System.Fabric.Description.ApplicationDescription.MaximumNodes" /> when application was created.</span></span>
                </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateApplicationUpgradeAsync (updateDescription As ApplicationUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para><span data-ttu-id="9e2ef-464">Beschreibung des zu ändernden Parameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-464">Description of parameters to modify.</span></span> <span data-ttu-id="9e2ef-465">Nicht angegeben, Parameter bleiben unverändert bleiben sollen, und ihren aktuellen Wert in der Aktualisierung beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-465">Unspecified parameters are left unmodified and will retain their current value in the upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-466">Ändert das Upgrade ein Upgrade der ausstehenden-Parameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-466">Modifies the upgrade parameters of a pending application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-467">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-467">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-468"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Anwendungsupgrades zu ändern.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-468"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending application upgrade to modify.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateApplicationUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateApplicationUpgradeAsync (System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateApplicationUpgradeAsync(class System.Fabric.Description.ApplicationUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpdateApplicationUpgradeAsync(System.Fabric.Description.ApplicationUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateApplicationUpgradeAsync : System.Fabric.Description.ApplicationUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpdateApplicationUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ApplicationUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para><span data-ttu-id="9e2ef-469">Beschreibung des zu ändernden Parameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-469">Description of parameters to modify.</span></span> <span data-ttu-id="9e2ef-470">Nicht angegeben, Parameter bleiben unverändert bleiben sollen, und ihren aktuellen Wert in der Aktualisierung beibehalten wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-470">Unspecified parameters are left unmodified and will retain their current value in the upgrade.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-471">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-471">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-472">Das Token, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-472">The token that the operation is observing.</span></span> <span data-ttu-id="9e2ef-473">Es kann verwendet werden, um eine Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-473">It can be used to propagate a notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-474">Ändert das Upgrade ein Upgrade der ausstehenden-Parameter.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-474">Modifies the upgrade parameters of a pending application upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-475">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-475">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-476"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: Es ist keine ausstehende Anwendungsupgrades zu ändern.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-476"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotUpgrading" />: There is no pending application upgrade to modify.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeApplicationAsync (upgradeDescription As ApplicationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para><span data-ttu-id="9e2ef-477">Die Beschreibung der Upgraderichtlinie und die Anwendung zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-477">The description of the upgrade policy and the application to be upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-478">Führt ein Upgrade auf eine Instanz der Anwendung an.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-478">Performs upgrade on an application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-479">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-479">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-480">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-480">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-481">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-481">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-482"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Das Upgrade ist in Bezug auf die bereitgestellten Manifeste ungültig.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-482"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The upgrade is invalid with respect to the provisioned manifests.</span></span> </para>
          <para>
            <span data-ttu-id="9e2ef-483"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: Der Anwendungstyp ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-483"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: The application type does not exist.</span></span> </para>
          <para>
            <span data-ttu-id="9e2ef-484"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-484"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-485"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-485"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-486"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-486"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-487"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung ist bereits auf die angeforderte Version aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-487"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is already being upgraded to the requested version.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-488">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-488">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-489">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-489">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-490">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-490">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-491">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-491">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="9e2ef-492"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-492"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-493">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-493">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-494">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-494">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeApplicationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeApplicationAsync (System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeApplicationAsync(class System.Fabric.Description.ApplicationUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ApplicationManagementClient.UpgradeApplicationAsync(System.Fabric.Description.ApplicationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeApplicationAsync : System.Fabric.Description.ApplicationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="applicationManagementClient.UpgradeApplicationAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.ApplicationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para><span data-ttu-id="9e2ef-495">Die Beschreibung der Aktualisierung Richtlinie und die Anwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-495">The description of the upgrade policy and the application to be upgraded.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="9e2ef-496">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-496">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="9e2ef-497">Das Token, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-497">The token that the operation is observing.</span></span> <span data-ttu-id="9e2ef-498">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-498">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="9e2ef-499">Führt ein Upgrade auf eine Instanz der Anwendung an.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-499">Performs upgrade on an application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="9e2ef-500">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-500">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="9e2ef-501">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="9e2ef-501">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="9e2ef-502">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-502">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="9e2ef-503"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Das Upgrade ist in Bezug auf die bereitgestellten Manifeste ungültig.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-503"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The upgrade is invalid with respect to the provisioned manifests.</span></span> </para>
          <para>
            <span data-ttu-id="9e2ef-504"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: Der Anwendungstyp ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-504"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeValidationError" />: The application type does not exist.</span></span> </para>
          <para>
            <span data-ttu-id="9e2ef-505"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-505"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="9e2ef-506"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-506"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="9e2ef-507"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-507"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="9e2ef-508"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung ist bereits auf die angeforderte Version aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-508"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is already being upgraded to the requested version.</span></span></para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="9e2ef-509">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-509">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="9e2ef-510">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-510">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="9e2ef-511">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-511">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="9e2ef-512">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-512">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="9e2ef-513"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-513"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="9e2ef-514">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-514">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="9e2ef-515">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="9e2ef-515">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>