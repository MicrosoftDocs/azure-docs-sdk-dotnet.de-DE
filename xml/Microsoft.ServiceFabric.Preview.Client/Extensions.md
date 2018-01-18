<Type Name="Extensions" FullName="Microsoft.ServiceFabric.Preview.Client.Extensions">
  <TypeSignature Language="C#" Value="public static class Extensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit Extensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Extensions" />
  <TypeSignature Language="VB.NET" Value="Public Module Extensions" />
  <TypeSignature Language="F#" Value="type Extensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5c272-101">Erweiterungsmethoden für FabricClient.</span><span class="sxs-lookup"><span data-stu-id="5c272-101">Extension methods for FabricClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-102"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-102"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentDescription">
          <para><span data-ttu-id="5c272-103">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-103">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> that describes the compose deployment to be created.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-104">Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="5c272-104">Creates and instantiates the Service Fabric compose deployment described by the compose deployment description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-105">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-105">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-106">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-106">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-107">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-107">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="5c272-108"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="5c272-108"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="5c272-109"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="5c272-109"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="5c272-110"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-110"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="5c272-111"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-111"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: The compose deployment has already been created.</span></span></para>
          <para>
            <span data-ttu-id="5c272-112"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-112"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created so that compose deployment can not be created using the same name.</span></span> </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="5c272-113">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-113">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="5c272-114">Eine erforderliche Datei wurde nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-114">A required file was not found .</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="5c272-115">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="5c272-115">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="5c272-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-116"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-117">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-117">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-118">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-118">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="5c272-119">Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.</span><span class="sxs-lookup"><span data-stu-id="5c272-119">The parameters specified via the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> are incorrect.</span></span>
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-120"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-120"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentDescription">
          <para><span data-ttu-id="5c272-121">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-121">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> that describes the compose deployment to be created.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-122">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5c272-122">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-123">Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="5c272-123">Creates and instantiates the Service Fabric compose deployment described by the compose deployment description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-124">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-124">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-125">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-125">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-126">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-126">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="5c272-127"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="5c272-127"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="5c272-128"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="5c272-128"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="5c272-129"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-129"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="5c272-130"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-130"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: The compose deployment has already been created.</span></span></para>
          <para>
            <span data-ttu-id="5c272-131"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-131"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created so that compose deployment can not be created using the same name.</span></span> </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="5c272-132">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-132">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="5c272-133">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-133">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="5c272-134">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-134">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="5c272-135">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="5c272-135">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="5c272-136"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-136"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-137">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-137">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-138">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-138">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="5c272-139">Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.</span><span class="sxs-lookup"><span data-stu-id="5c272-139">The parameters specified via the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> are incorrect.</span></span>
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-140"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-140"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentDescription">
          <para><span data-ttu-id="5c272-141">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-141">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> that describes the compose deployment to be created.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-142">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5c272-142">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5c272-143">Das CancellationToken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5c272-143">The CancellationToken that the operation is observing.</span></span> <span data-ttu-id="5c272-144">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-144">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-145">Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</span><span class="sxs-lookup"><span data-stu-id="5c272-145">Creates and instantiates the Service Fabric compose deployment described by the compose deployment description.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-146">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-146">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-147">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-147">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-148">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-148">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="5c272-149"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</span><span class="sxs-lookup"><span data-stu-id="5c272-149"><see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: The create application request is not valid with respect to the provisioned manifests for the requested application type.</span></span></para>
          <para>
            <span data-ttu-id="5c272-150"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</span><span class="sxs-lookup"><span data-stu-id="5c272-150"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: The application name is not a valid Naming URI.</span></span></para>
          <para>
            <span data-ttu-id="5c272-151"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-151"><see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: A corrupted file was encountered on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="5c272-152"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-152"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: The compose deployment has already been created.</span></span></para>
          <para>
            <span data-ttu-id="5c272-153"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="5c272-153"><see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: The application has already been created so that compose deployment can not be created using the same name.</span></span> </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="5c272-154">Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-154">There was an error accessing a file on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="5c272-155">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-155">A required file was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="5c272-156">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="5c272-156">A required directory was not found on the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="5c272-157">Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="5c272-157">A path to an Image Store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <span data-ttu-id="5c272-158"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="5c272-158"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the Image Store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-159">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-159">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-160">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-160">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                <span data-ttu-id="5c272-161">Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.</span><span class="sxs-lookup"><span data-stu-id="5c272-161">The parameters specified via the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> are incorrect.</span></span>
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-162"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-162"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="description">
          <para><span data-ttu-id="5c272-163">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-163">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> that determines which compose deployment should be deleted.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-164">Löscht die verfassen Bereitstellung-Instanz aus dem Cluster an.</span><span class="sxs-lookup"><span data-stu-id="5c272-164">Deletes the compose deployment instance from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-165">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-165">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5c272-166">Alle verfassen Bereitstellungszustand verloren und kann nicht wiederhergestellt werden, nachdem die Bereitstellung verfassen gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="5c272-166">All compose deployment state will be lost and cannot be recovered after the compose deployment is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-167">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-167">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-168">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-168">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="5c272-169"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5c272-169"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: The compose deployment does not exist.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="5c272-170"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="5c272-170"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-171">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-171">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-172">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-172">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-173"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-173"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="description">
          <para><span data-ttu-id="5c272-174">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-174">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> that determines which compose deployment should be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-175">Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</span><span class="sxs-lookup"><span data-stu-id="5c272-175">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-176">Löscht die Compose-Bereitstellung aus dem Cluster an.</span><span class="sxs-lookup"><span data-stu-id="5c272-176">Deletes the compose deployment from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-177">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-177">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5c272-178">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5c272-178">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-179">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-179">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-180">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-180">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="5c272-181"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5c272-181"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: The compose deployment does not exist.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="5c272-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="5c272-182"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-183">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-183">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-184">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-184">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-185"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-185"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="description">
          <para><span data-ttu-id="5c272-186">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-186">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> that determines which compose deployment should be deleted.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-187">Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</span><span class="sxs-lookup"><span data-stu-id="5c272-187">Defines the maximum amount of time the system will allow this operation to continue before returning System.TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5c272-188">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="5c272-188">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="5c272-189">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-189">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-190">Löscht die Compose-Bereitstellung aus dem Cluster an.</span><span class="sxs-lookup"><span data-stu-id="5c272-190">Deletes the compose deployment from the cluster.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-191">Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-191">A <see cref="T:System.Threading.Tasks.Task" /> representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="5c272-192">Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</span><span class="sxs-lookup"><span data-stu-id="5c272-192">All application state will be lost and cannot be recovered after the application is deleted.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-193">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-193">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-194">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-194">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="5c272-195"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5c272-195"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: The compose deployment does not exist.</span></span>
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <span data-ttu-id="5c272-196"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="5c272-196"><see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: The application is being upgraded.</span></span> </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-197">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-197">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-198">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-198">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-199"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-199"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentQueryDescription">
          <para><span data-ttu-id="5c272-200">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="5c272-200">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> that determines which compose deployments should be queried.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-201">Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5c272-201">Gets the status of compose deployments created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="5c272-202">Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="5c272-202">If the compose deployments do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-203">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-203">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="5c272-204">Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="5c272-204">The value of TResult parameter is an <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> that represents the list of compose deployments that respect the filters in the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="5c272-205">Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5c272-205">If the provided query description has no matching compose deployments, it will return a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="5c272-206">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-206">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="5c272-207">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-207">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="5c272-208">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="5c272-208">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription, timeout As TimeSpan) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-209"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-209"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentQueryDescription">
          <para><span data-ttu-id="5c272-210">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="5c272-210">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> that determines which compose deployments should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-211">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5c272-211">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-212">Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5c272-212">Gets the status of compose deployments created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="5c272-213">Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="5c272-213">If the compose deployments do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-214">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-214">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="5c272-215">Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="5c272-215">The value of TResult parameter is an <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> that represents the list of compose deployments that respect the filters in the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="5c272-216">Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5c272-216">If the provided query description has no matching compose deployments, it will return a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="5c272-217">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-217">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="5c272-218">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-218">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="5c272-219">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="5c272-219">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-220"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-220"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="composeDeploymentQueryDescription">
          <para><span data-ttu-id="5c272-221">Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="5c272-221">The <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> that determines which compose deployments should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="5c272-222">Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="5c272-222">Defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="5c272-223">Das CancellationToken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5c272-223">The CancellationToken that the operation is observing.</span></span> <span data-ttu-id="5c272-224">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c272-224">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-225">Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="5c272-225">Gets the status of compose deployments created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="5c272-226">Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="5c272-226">If the compose deployments do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-227">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="5c272-227">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="5c272-228">Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="5c272-228">The value of TResult parameter is an <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> that represents the list of compose deployments that respect the filters in the <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="5c272-229">Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="5c272-229">If the provided query description has no matching compose deployments, it will return a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="5c272-230">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-230">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="5c272-231">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="5c272-231">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="5c272-232">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="5c272-232">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync(System.Fabric.FabricClient.ComposeDeploymentClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentUpgradeProgressAsync (client As FabricClient.ComposeDeploymentClient, deploymentName As String) As Task(Of ComposeDeploymentUpgradeProgress)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentUpgradeProgressAsync : System.Fabric.FabricClient.ComposeDeploymentClient * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync (client, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="client">
          <span data-ttu-id="5c272-233"><see cref="T:System.Fabric.FabricClient" />-Objekt</span><span class="sxs-lookup"><span data-stu-id="5c272-233"><see cref="T:System.Fabric.FabricClient" /> object.</span></span></param>
        <param name="deploymentName">
          <para><span data-ttu-id="5c272-234">Der Name der Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="5c272-234">The name of the deployment.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="5c272-235">Ruft ab, das Upgrade Status der angegebenen Bereitstellung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5c272-235">Retrieves the upgrade progress of the specified compose deployment.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="5c272-236">Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht der upgradeverlauf des angegebenen Bereitstellung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="5c272-236">A <see cref="T:System.Threading.Tasks.Task" /> whose result is the upgrade progress of the specified compose deployment.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="5c272-237">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="5c272-237">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="5c272-238">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c272-238">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="5c272-239"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="5c272-239"><see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: The compose deployment does not exist.</span></span>
            </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="5c272-240">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="5c272-240">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="5c272-241">Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</span><span class="sxs-lookup"><span data-stu-id="5c272-241">The request was canceled before the timeout expired but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpgradeComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, upgradeDescription As ComposeDeploymentUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <summary>
          <para><span data-ttu-id="5c272-242">Startet das Upgrade für das Verfassen Bereitstellung durch den Namen der Bereitstellung im Cluster identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5c272-242">Starts the upgrade for the compose deployment identified by the deployment name, in the cluster.</span></span></para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
          <para><span data-ttu-id="5c272-243">Startet das Upgrade für das Verfassen Bereitstellung durch den Namen der Bereitstellung im Cluster identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5c272-243">Starts the upgrade for the compose deployment identified by the deployment name, in the cluster.</span></span></para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>