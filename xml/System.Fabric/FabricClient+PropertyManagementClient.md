<Type Name="FabricClient+PropertyManagementClient" FullName="System.Fabric.FabricClient+PropertyManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/PropertyManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.PropertyManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.PropertyManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.PropertyManagementClient = class" />
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
      <para><span data-ttu-id="2cc07-101">Stellt die Eigenschaft Verwaltungsclient verwendet, um die Verwaltung von Namen und Eigenschaften ausführen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-101">Represents the property management client used to perform management of names and properties.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-102">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-102">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-103">Erstellt den angegebenen Service Fabric-Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-103">Creates the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-104">Erstellungsvorgang für eine Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-104">A task that represents the asynchronous create operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-105">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-105">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-106">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-106">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-107">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-107">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-108">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-108">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-109">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-109">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="2cc07-110"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />wird zurückgegeben, wenn die Service Fabric-Name ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-110"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" /> is returned when the Service Fabric name already exists.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-111">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-111">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-112">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-112">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-113">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-113">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-114">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-114">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-115">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-115">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-116"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-117">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-117">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-118">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-118">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.CreateNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.CreateNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-119">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-119">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-120">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-120">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-121">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-121">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-122">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-122">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-123">Erstellt den angegebenen Service Fabric-Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-123">Creates the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-124">Erstellungsvorgang für eine Aufgabe, die den asynchronen darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-124">A task that represents the asynchronous create operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-125">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-125">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-126">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-126">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-127">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-127">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-128">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-128">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-129">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-129">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <span data-ttu-id="2cc07-130"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" />wird zurückgegeben, wenn die Service Fabric-Name ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-130"><see cref="F:System.Fabric.FabricErrorCode.NameAlreadyExists" /> is returned when the Service Fabric name already exists.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-131">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-131">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-132">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-132">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-133">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-133">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-134">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-134">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-135">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-135">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-136"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-136"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-137">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-137">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-138">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-138">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNameAsync (name As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-139">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-139">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-140">Löscht den angegebenen Service Fabric-Namen an.</span><span class="sxs-lookup"><span data-stu-id="2cc07-140">Deletes the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-141">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-141">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-142">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-142">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-143">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-143">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-144">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-144">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-145">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-145">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-146">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-146">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-147">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-147">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-148"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-148"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-149">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-149">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-150">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-150">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-151">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-151">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-152">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-152">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-153">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-153">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-154"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-154"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-155"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />wird zurückgegeben, wenn <paramref name="name" /> übergeordnete Element eines anderen Namen, Eigenschaften oder eines Diensts ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-155"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" /> is returned when <paramref name="name" /> is parent of other Names, Properties or a Service.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-156">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-156">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-157">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-157">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNameAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNameAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeleteNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeleteNameAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-158">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-158">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-159">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-159">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-160">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-160">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-161">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-161">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-162">Löscht den angegebenen Service Fabric-Namen an.</span><span class="sxs-lookup"><span data-stu-id="2cc07-162">Deletes the specified Service Fabric name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-163">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-163">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-164">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-164">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-165">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-165">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-166">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-166">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-167">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-167">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-168">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-168">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-169">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-169">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-170"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-170"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-171">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-171">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-172">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-172">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-173">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-173">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-174">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-174">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-175">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-175">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-176"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-176"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-177"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" />wird zurückgegeben, wenn <paramref name="name" /> übergeordnete Element eines anderen Namen, Eigenschaften oder eines Diensts ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-177"><see cref="F:System.Fabric.FabricErrorCode.NameNotEmpty" /> is returned when <paramref name="name" /> is parent of other Names, Properties or a Service.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-178">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-178">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-179">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-179">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeletePropertyAsync (parentName As Uri, propertyName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-180">Der übergeordnete Service Fabric-Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-180">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-181">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-181">The name of the Service Fabric property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-182">Löscht die angegebene Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-182">Deletes the specified Service Fabric property.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-183">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-183">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-184">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-184">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-185">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-185">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-186">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-186">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-187">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-187">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-188">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-188">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-189">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-189">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-190"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-190"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-191"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-191"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-192">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-192">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-193"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-193"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-194">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-194">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-195">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-195">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-196">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-196">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-197">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-197">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-198">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-198">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-199"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-199"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-200">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-200">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-201">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-201">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeletePropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeletePropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeletePropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.DeletePropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeletePropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.DeletePropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-202">URI definiert den übergeordneten Service Fabric-Namen der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-202">URI defines the parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-203">Zeichenfolge definiert den Namen der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-203">String defines the name of the Service Fabric property.</span></span></para>
        </param>
        <param name="timeout">
          <para>
            <span data-ttu-id="2cc07-204"><see cref="T:System.TimeSpan" />definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-204"><see cref="T:System.TimeSpan" /> defines the maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para>
            <span data-ttu-id="2cc07-205"><see cref="T:System.Threading.CancellationToken" />dass der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-205"><see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-206">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-206">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-207">Löscht die angegebene Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-207">Deletes the specified Service Fabric property.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-208">Eine Aufgabe, die den asynchronen Löschvorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-208">A task that represents the asynchronous delete operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-209">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-209">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-210">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-210">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-211">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-211">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-212">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-212">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-213">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-213">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-214">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-214">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-215"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-215"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-216"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-216"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-217">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-217">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-218"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-218"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-219">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-219">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-220">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-220">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-221">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-221">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-222">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-222">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-223">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-223">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-224"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-225">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-225">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-226">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-226">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumeratePropertiesAsync (name As Uri, includeValues As Boolean, previousResult As PropertyEnumerationResult) As Task(Of PropertyEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-227">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-227">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="includeValues">
          <para>
            <span data-ttu-id="2cc07-228"><languageKeyword>"True"</languageKeyword> Wenn Werte mit den Metadaten zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-228"><languageKeyword>True</languageKeyword> if values should be returned with the metadata.</span></span> <span data-ttu-id="2cc07-229"><languageKeyword>"False"</languageKeyword> zurückzugebenden nur Eigenschaftsmetadaten; <languageKeyword>"true"</languageKeyword> Eigenschaftsmetadaten und-Wert zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2cc07-229"><languageKeyword>False</languageKeyword> to return only property metadata; <languageKeyword>true</languageKeyword> to return property metadata and value.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="2cc07-230">Das batchergebnis für den vorhergehenden Aufruf.</span><span class="sxs-lookup"><span data-stu-id="2cc07-230">The batch result for the previous call.</span></span> <span data-ttu-id="2cc07-231">Wenn dies der erste Aufruf, dieses Feld muss festgelegt werden auf Null.</span><span class="sxs-lookup"><span data-stu-id="2cc07-231">If this the first call, this field needs to be set to null.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-232">Listet alle Service Fabric-Eigenschaften unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-232">Enumerates all Service Fabric properties under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-233">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-233">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-234">Wenn <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> ist "true", und klicken Sie dann das Ergebnis als Eingabe für den nächsten verwendet werden kann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> aufrufen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-234">If <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> is true, then this result can be used as input to the next <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> call.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-235">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-235">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-236">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-236">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-237">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-237">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-238">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-238">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-239">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-239">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-240">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-240">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-241"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-241"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-242">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-242">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-243">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-243">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-244">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-244">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-245">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-245">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-246">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-246">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-247"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-247"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="2cc07-248">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-248">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-249">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-249">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumeratePropertiesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync (Uri name, bool includeValues, System.Fabric.PropertyEnumerationResult previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyEnumerationResult&gt; EnumeratePropertiesAsync(class System.Uri name, bool includeValues, class System.Fabric.PropertyEnumerationResult previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumeratePropertiesAsync : Uri * bool * System.Fabric.PropertyEnumerationResult * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;" Usage="propertyManagementClient.EnumeratePropertiesAsync (name, includeValues, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="includeValues" Type="System.Boolean" />
        <Parameter Name="previousResult" Type="System.Fabric.PropertyEnumerationResult" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-250">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-250">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="includeValues">
          <para>
            <span data-ttu-id="2cc07-251"><languageKeyword>"True"</languageKeyword> , wenn die Werte mit den Metadaten zurückgegeben werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-251"><languageKeyword>True</languageKeyword> if the values should be returned with the metadata.</span></span>
                <span data-ttu-id="2cc07-252"><languageKeyword>"False"</languageKeyword> zurückzugebenden nur Eigenschaftsmetadaten; "true" zurückgeben Eigenschaftsmetadaten und-Wert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-252"><languageKeyword>False</languageKeyword> to return only property metadata; true to return property metadata and value.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="2cc07-253">Das batchergebnis für den vorhergehenden Aufruf.</span><span class="sxs-lookup"><span data-stu-id="2cc07-253">The batch result for the previous call.</span></span> <span data-ttu-id="2cc07-254">Wenn dies der erste Aufruf, dieses Feld muss festgelegt werden auf Null.</span><span class="sxs-lookup"><span data-stu-id="2cc07-254">If this the first call, this field needs to be set to null.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-255">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-255">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-256">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-256">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-257">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-257">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-258">Listet alle Service Fabric-Eigenschaften unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-258">Enumerates all Service Fabric properties under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-259">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-259">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-260">Wenn <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> ist "true", und klicken Sie dann das Ergebnis als Eingabe für den nächsten verwendet werden kann <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> aufrufen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-260">If <see cref="P:System.Fabric.PropertyEnumerationResult.HasMoreData" /> is true, then this result can be used as input to the next <see cref="M:System.Fabric.FabricClient.PropertyManagementClient.EnumeratePropertiesAsync(System.Uri,System.Boolean,System.Fabric.PropertyEnumerationResult)" /> call.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-261">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-261">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-262">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-262">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-263">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-263">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-264">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-264">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-265">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-265">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-266">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-266">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-267"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-267"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-268">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-268">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-269">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-269">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-270">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-270">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-271">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-271">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-272">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-272">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-273"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-273"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="2cc07-274">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-274">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-275">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-275">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function EnumerateSubNamesAsync (name As Uri, previousResult As NameEnumerationResult, recursive As Boolean) As Task(Of NameEnumerationResult)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-276">Der Name der übergeordneten Service Fabric aufgelistet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-276">The parent Service Fabric name to be enumerated.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="2cc07-277">Das Ergebnis, das von der vorherigen Enumerate-Aufruf zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-277">The result that was returned by the previous enumerate call.</span></span> <span data-ttu-id="2cc07-278">Bei dem ersten Aufruf ist dies null.</span><span class="sxs-lookup"><span data-stu-id="2cc07-278">For the initial call, this is null.</span></span></para>
        </param>
        <param name="recursive">
          <para>
            <span data-ttu-id="2cc07-279"><languageKeyword>"True"</languageKeyword> die Enumeration rekursiv sein soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-279"><languageKeyword>True</languageKeyword> the enumeration should be recursive.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-280">Listet die Namen aller Service Fabric unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-280">Enumerates all the Service Fabric names under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-281">Eine Aufgabe, die den asynchronen stellt zählt Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-281">A task that represents the asynchronous enumerate operation.</span></span></para>
          <para><span data-ttu-id="2cc07-282">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NameEnumerationResult" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-282">See <see cref="T:System.Fabric.NameEnumerationResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-283">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-283">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-284">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-284">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-285">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-285">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-286">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-286">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-287">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-287">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="2cc07-288"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-288"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-289">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-289">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-290">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-290">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-291">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-291">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-292">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-292">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-293">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-293">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-294"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-294"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-295">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-295">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-296">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-296">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="EnumerateSubNamesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync (Uri name, System.Fabric.NameEnumerationResult previousResult, bool recursive, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NameEnumerationResult&gt; EnumerateSubNamesAsync(class System.Uri name, class System.Fabric.NameEnumerationResult previousResult, bool recursive, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.EnumerateSubNamesAsync(System.Uri,System.Fabric.NameEnumerationResult,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnumerateSubNamesAsync : Uri * System.Fabric.NameEnumerationResult * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;" Usage="propertyManagementClient.EnumerateSubNamesAsync (name, previousResult, recursive, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NameEnumerationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.NameEnumerationResult" />
        <Parameter Name="recursive" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-297">Der Name der übergeordneten Service Fabric aufgelistet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-297">The parent Service Fabric name to be enumerated.</span></span></para>
        </param>
        <param name="previousResult">
          <para><span data-ttu-id="2cc07-298">Das Ergebnis, das von der vorherigen Enumerate-Aufruf zurückgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-298">The result that was returned by the previous enumerate call.</span></span> <span data-ttu-id="2cc07-299">Bei dem ersten Aufruf ist dies null.</span><span class="sxs-lookup"><span data-stu-id="2cc07-299">For the initial call, this is null.</span></span></para>
        </param>
        <param name="recursive">
          <para>
            <span data-ttu-id="2cc07-300"><languageKeyword>"True"</languageKeyword> , wenn die Enumeration rekursiv sein soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-300"><languageKeyword>True</languageKeyword> if the enumeration should be recursive.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-301">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-301">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-302">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-302">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-303">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-303">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-304">Listet die Namen aller Service Fabric unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-304">Enumerates all the Service Fabric names under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-305">Eine Aufgabe, die den asynchronen stellt zählt Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-305">A task that represents the asynchronous enumerate operation.</span></span></para>
          <para><span data-ttu-id="2cc07-306">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NameEnumerationResult" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-306">See <see cref="T:System.Fabric.NameEnumerationResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-307">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-307">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-308">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-308">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-309">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-309">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-310">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-310">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-311">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-311">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="2cc07-312"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-312"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-313">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-313">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-314">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-314">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-315">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-315">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-316">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-316">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-317">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-317">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-318"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-318"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-319">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-319">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-320">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-320">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyAsync (parentName As Uri, propertyName As String) As Task(Of NamedProperty)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-321">Der übergeordnete Service Fabric-Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-321">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-322">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-322">The name of the Service Fabric property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-323">Ruft den angegebenen <see cref="T:System.Fabric.NamedProperty" /> ab.</span><span class="sxs-lookup"><span data-stu-id="2cc07-323">Gets the specified <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-324">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-324">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-325">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedProperty" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-325">See <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-326">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-326">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-327">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-327">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-328">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-328">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-329">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-329">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-330">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-330">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-331">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-331">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-332"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-332"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-333"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-333"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-334">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-334">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-335">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-335">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-336">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-336">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-337">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-337">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-338">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-338">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-339"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-339"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-340">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-340">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-341">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-341">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt; GetPropertyAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedProperty&gt; GetPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;" Usage="propertyManagementClient.GetPropertyAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-342">Der übergeordnete Service Fabric-Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-342">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-343">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-343">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-344">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-344">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-345">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-345">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-346">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-346">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-347">Ruft den angegebenen <see cref="T:System.Fabric.NamedProperty" /> ab.</span><span class="sxs-lookup"><span data-stu-id="2cc07-347">Gets the specified <see cref="T:System.Fabric.NamedProperty" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-348">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-348">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-349">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedProperty" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-349">See <see cref="T:System.Fabric.NamedProperty" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-350">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-350">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-351">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-351">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-352">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-352">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-353">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-353">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-354">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-354">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-355">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-355">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-356"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-356"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-357"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-357"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-358">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-358">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-359">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-359">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-360">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-360">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-361">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-361">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-362">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-362">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-363"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-363"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-364">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-364">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-365">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-365">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPropertyMetadataAsync (parentName As Uri, propertyName As String) As Task(Of NamedPropertyMetadata)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-366">Der übergeordnete Service Fabric-Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-366">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-367">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-367">The name of the Property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-368">Ruft den angegebenen <see cref="T:System.Fabric.NamedPropertyMetadata" /> ab.</span><span class="sxs-lookup"><span data-stu-id="2cc07-368">Gets the specified <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-369">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-369">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-370">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-370">See <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-371">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-371">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-372">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-372">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-373">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-373">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-374">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-374">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-375">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-375">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-376">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-376">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-377"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-377"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-378"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-378"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-379">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-379">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-380">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-380">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-381">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-381">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-382">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-382">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-383">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-383">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-384"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-384"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-385">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-385">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-386">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-386">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPropertyMetadataAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync (Uri parentName, string propertyName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.NamedPropertyMetadata&gt; GetPropertyMetadataAsync(class System.Uri parentName, string propertyName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.GetPropertyMetadataAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPropertyMetadataAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;" Usage="propertyManagementClient.GetPropertyMetadataAsync (parentName, propertyName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NamedPropertyMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-387">Der übergeordnete Service Fabric-Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-387">The parent Service Fabric name of the property.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-388">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-388">The name of the Property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-389">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-389">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-390">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-390">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="2cc07-391">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-391">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-392">Ruft den angegebenen <see cref="T:System.Fabric.NamedPropertyMetadata" /> ab.</span><span class="sxs-lookup"><span data-stu-id="2cc07-392">Gets the specified <see cref="T:System.Fabric.NamedPropertyMetadata" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-393">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-393">A task that represents the asynchronous get operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-394">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-394">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-395">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-395">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-396">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-396">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-397">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-397">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-398">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-398">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-399">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-399">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-400"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-400"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-401"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" />wird zurückgegeben, wenn die angegebene Eigenschaft nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-401"><see cref="F:System.Fabric.FabricErrorCode.PropertyNotFound" /> is returned when the specified Property does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-402">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-402">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-403">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-403">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-404">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-404">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-405">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-405">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-406">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-406">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-407"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>    
                <span data-ttu-id="2cc07-408">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-408">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-409">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-409">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function NameExistsAsync (name As Uri) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-410">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-410">The Service Fabric name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-411">Gibt <languageKeyword>"true"</languageKeyword> , wenn der angegebene Name der Service Fabric ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-411">Returns <languageKeyword>true</languageKeyword> if the specified Service Fabric name exists.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-412">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-412">A task that represents the asynchronous operation.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-413"><languageKeyword>"true"</languageKeyword> Wenn der angegebene Service Fabric-Namen vorhanden ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="2cc07-413"><languageKeyword>true</languageKeyword> if the specified Service Fabric name exists; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-414">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-414">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
          <para>
            <span data-ttu-id="2cc07-415"><see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />ist der unidirektionale überprüfen, ob des Clusters aktiv ist und <see cref="T:System.Fabric.FabricClient" /> können mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-415"><see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> is the one way of verifying the cluster is up and <see cref="T:System.Fabric.FabricClient" /> can connect to the cluster.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-416">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-416">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-417">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-417">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-418">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-418">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-419">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-419">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-420">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-420">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-421">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-421">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-422">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-422">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-423">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-423">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-424">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-424">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-425"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-425"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-426">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-426">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-427">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-427">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NameExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NameExistsAsync (Uri name, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NameExistsAsync(class System.Uri name, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.NameExistsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.NameExistsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="propertyManagementClient.NameExistsAsync (name, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-428">Der Name des Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-428">The Service Fabric name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-429">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-429">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-430">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-430">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-431">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-431">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-432">Gibt <languageKeyword>"true"</languageKeyword> , wenn der angegebene Name der Service Fabric ist vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-432">Returns <languageKeyword>true</languageKeyword> if the specified Service Fabric name exists.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-433">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-433">A task that represents the asynchronous operation.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-434"><languageKeyword>"true"</languageKeyword> Wenn der angegebene Service Fabric-Namen vorhanden ist, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="2cc07-434"><languageKeyword>true</languageKeyword> if the specified Service Fabric name exists; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-435">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-435">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-436">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-436">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-437">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-437">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-438">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-438">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-439">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-439">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-440">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-440">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-441">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-441">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-442">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-442">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-443">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-443">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-444"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-445">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-445">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-446">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-446">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutCustomPropertyOperationAsync (name As Uri, operation As PutCustomPropertyOperation) As Task" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-447">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-447">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="operation">
          <para><span data-ttu-id="2cc07-448">Die put-Vorgang-Parameter, einschließlich Namen, Wert und benutzerdefinierte Typinformationen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-448">The put operation parameters, including property name, value and custom type information.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-449">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft von beschriebenen <see cref="T:System.Fabric.PutCustomPropertyOperation" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-449">Creates or updates the specified Service Fabric property described by <see cref="T:System.Fabric.PutCustomPropertyOperation" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-450">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-450">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-451">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-451">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-452">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-452">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-453">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-453">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-454">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-454">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-455">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-455">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-456"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-456"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-457">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-457">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-458"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-458"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-459">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-459">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-460">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-460">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-461">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-461">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-462">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-462">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-463">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-463">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-464"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-465"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-465"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-466">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-466">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-467">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-467">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutCustomPropertyOperationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutCustomPropertyOperationAsync (Uri name, System.Fabric.PutCustomPropertyOperation operation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutCustomPropertyOperationAsync(class System.Uri name, class System.Fabric.PutCustomPropertyOperation operation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutCustomPropertyOperationAsync(System.Uri,System.Fabric.PutCustomPropertyOperation,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutCustomPropertyOperationAsync : Uri * System.Fabric.PutCustomPropertyOperation * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutCustomPropertyOperationAsync (name, operation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="operation" Type="System.Fabric.PutCustomPropertyOperation" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="2cc07-468">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-468">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="operation">
          <para><span data-ttu-id="2cc07-469">Die put-Vorgang-Parameter, einschließlich Namen, Wert und benutzerdefinierte Typinformationen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-469">The put operation parameters, including property name, value and custom type information.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-470">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-470">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-471">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-471">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="2cc07-472">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-472">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-473">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft von beschriebenen <see cref="T:System.Fabric.PutCustomPropertyOperation" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-473">Creates or updates the specified Service Fabric property described by <see cref="T:System.Fabric.PutCustomPropertyOperation" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-474">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-474">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-475">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-475">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-476">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-476">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-477">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-477">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-478">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-478">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-479">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-479">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-480"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="name" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-480"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="name" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-481">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-481">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-482"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-482"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-483">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-483">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-484">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-484">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-485">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-485">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-486">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-486">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-487">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-487">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-488"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="name" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-488"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="name" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-489"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-489"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <see cref="P:System.Fabric.PutCustomPropertyOperation.PropertyValue" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-490">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-490">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-491">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-491">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-492">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-492">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-493">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-493">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-494">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-494">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-495">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Byte" /> Array unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-495">Creates or updates the specified Service Fabric property of type <see cref="T:System.Byte" /> array under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-496">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-496">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-497">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-497">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-498">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-498">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-499">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-499">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-500">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-500">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-501">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-501">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-502">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-502">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-503"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-503"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-504">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-504">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-505"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-505"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-506">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-506">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-507">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-507">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-508">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-508">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-509">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-509">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-510">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-510">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-511"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-511"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-512"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-512"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-513">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-513">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-514">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-514">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Double) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-515">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-515">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-516">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-516">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-517">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-517">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-518">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Double" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-518">Creates or updates the specified Service Fabric property of type <see cref="T:System.Double" /> under a given name.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-519">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-519">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-520">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-520">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-521">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-521">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-522">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-522">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-523">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-523">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-524">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-524">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-525">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-525">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-526"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-526"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-527">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-527">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-528"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-528"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-529">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-529">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-530">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-530">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-531">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-531">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-532">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-532">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-533">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-533">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-534"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-534"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-535"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-535"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-536">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-536">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-537">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-537">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-538">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-538">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-539">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-539">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-540">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-540">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-541">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Guid" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-541">Creates or updates the specified Service Fabric property of type <see cref="T:System.Guid" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-542">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-542">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-543">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-543">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-544">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-544">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-545">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-545">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-546">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-546">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-547">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-547">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-548">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-548">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-549"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-549"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-550">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-550">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-551"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-551"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-552">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-552">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-553">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-553">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-554">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-554">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-555">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-555">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-556">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-556">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-557"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-558"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-558"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-559">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-559">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-560">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-560">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-561">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-561">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-562">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-562">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-563">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-563">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-564">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Int64" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-564">Creates or updates the specified Service Fabric property of type <see cref="T:System.Int64" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-565">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-565">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-566">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-566">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-567">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-567">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-568">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-568">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-569">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-569">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-570">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-570">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-571">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-571">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-572"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-572"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-573">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-573">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-574"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-574"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-575">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-575">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-576">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-576">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-577">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-577">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-578">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-578">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-579">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-579">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-580"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-580"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-581"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-581"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-582">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-582">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-583">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-583">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function PutPropertyAsync (parentName As Uri, propertyName As String, value As String) As Task" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-584">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-584">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-585">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-585">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-586">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-586">The value of the property.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-587">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.String" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-587">Creates or updates the specified Service Fabric property of type <see cref="T:System.String" /> under a given name.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-588">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-588">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-589">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-589">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-590">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-590">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-591">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-591">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-592">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-592">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-593">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-593">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-594">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-594">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-595"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-595"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-596">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-596">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-597"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-597"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-598">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-598">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-599">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-599">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-600">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-600">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-601">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-601">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-602">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-602">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-603"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-603"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-604"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-604"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-605">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-605">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-606">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-606">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, byte[] value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, unsigned int8[] value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-607">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-607">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-608">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-608">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-609">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-609">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-610">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-610">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-611">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-611">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="2cc07-612">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-612">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-613">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Byte" /> Array unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-613">Creates or updates the specified Service Fabric property of type <see cref="T:System.Byte" /> array under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-614">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-614">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-615">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-615">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-616">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-616">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-617">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-617">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-618">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-618">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-619">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-619">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-620">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-620">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-621"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-621"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-622">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-622">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-623"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-623"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-624">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-624">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-625">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-625">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-626">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-626">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-627">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-627">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-628">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-628">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-629"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-629"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-630"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-630"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-631">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-631">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-632">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-632">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, double value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, float64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Double,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * double * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-633">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-633">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-634">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-634">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-635">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-635">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-636">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-636">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-637">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-637">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-638">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-638">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-639">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Double" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-639">Creates or updates the specified Service Fabric property of type <see cref="T:System.Double" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-640">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-640">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-641">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-641">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-642">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-642">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-643">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-643">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-644">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-644">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-645">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-645">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-646">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-646">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-647"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-647"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-648">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-648">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-649"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-649"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-650">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-650">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-651">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-651">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-652">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-652">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-653">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-653">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-654">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-654">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-655"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-655"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-656"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-656"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-657">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-657">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-658">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-658">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, Guid value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, valuetype System.Guid value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-659">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-659">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-660">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-660">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-661">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-661">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-662">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-662">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-663">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-663">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>
            <span data-ttu-id="2cc07-664">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-664">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-665">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Guid" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-665">Creates or updates the specified Service Fabric property of type <see cref="T:System.Guid" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-666">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-666">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-667">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-667">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-668">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-668">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-669">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-669">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-670">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-670">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-671">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-671">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-672">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-672">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-673"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-673"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-674">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-674">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-675"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-675"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-676">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-676">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-677">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-677">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-678">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-678">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-679">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-679">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-680">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-680">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-681"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-681"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-682"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-682"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-683">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-683">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-684">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-684">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, long value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, int64 value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-685">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-685">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-686">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-686">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-687">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-687">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-688">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-688">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-689">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-689">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-690">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-690">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-691">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.Int64" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-691">Creates or updates the specified Service Fabric property of type <see cref="T:System.Int64" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-692">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-692">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-693">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-693">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-694">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-694">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-695">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-695">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-696">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-696">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-697">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-697">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-698">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-698">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-699"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-699"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-700">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-700">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-701"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-701"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-702">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-702">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-703">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-703">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-704">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-704">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-705">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-705">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-706">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-706">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-707"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-708"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-708"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-709">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-709">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-710">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-710">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="PutPropertyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PutPropertyAsync (Uri parentName, string propertyName, string value, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task PutPropertyAsync(class System.Uri parentName, string propertyName, string value, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.PutPropertyAsync(System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.PutPropertyAsync : Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="propertyManagementClient.PutPropertyAsync (parentName, propertyName, value, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-711">Der Name des übergeordneten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-711">The parent Service Fabric name.</span></span></para>
        </param>
        <param name="propertyName">
          <para><span data-ttu-id="2cc07-712">Der Name der Service Fabric-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-712">The name of the Service Fabric property.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="2cc07-713">Der Wert der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="2cc07-713">The value of the property.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-714">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-714">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-715">Der Vorgang wurde beobachtet.</span><span class="sxs-lookup"><span data-stu-id="2cc07-715">The operation is observing.</span></span> <span data-ttu-id="2cc07-716">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-716">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-717">Erstellt oder aktualisiert die angegebene Service Fabric-Eigenschaft des Typs <see cref="T:System.String" /> unter einem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-717">Creates or updates the specified Service Fabric property of type <see cref="T:System.String" /> under a given name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-718">Eine Aufgabe, die den asynchronen stellt put Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2cc07-718">A task that represents the asynchronous put operation.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-719">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-719">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-720">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-720">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-721">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-721">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-722">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-722">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-723">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-723">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-724">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-724">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-725"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-725"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-726">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-726">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-727"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-727"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-728">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-728">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-729">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-729">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-730">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-730">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-731">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-731">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-732">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-732">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-733"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-734"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn <paramref name="value" /> ist größer als 1 MB.</span><span class="sxs-lookup"><span data-stu-id="2cc07-734"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when <paramref name="value" /> is larger than 1MB.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-735">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-735">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-736">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-736">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation})" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitPropertyBatchAsync (parentName As Uri, operations As ICollection(Of PropertyBatchOperation)) As Task(Of PropertyBatchResult)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-737">Der Name der übergeordneten Service Fabric unter dem die Eigenschaft Batchvorgänge ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-737">The parent Service Fabric name under which the Property batch operations will be executed.</span></span></para>
        </param>
        <param name="operations">
          <para><span data-ttu-id="2cc07-738">Die Eigenschaft Batchvorgänge.</span><span class="sxs-lookup"><span data-stu-id="2cc07-738">The batch property operations.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-739">Übermittelt einen Befehlsbatch <see cref="T:System.Fabric.PropertyBatchOperation" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-739">Submits a batch of <see cref="T:System.Fabric.PropertyBatchOperation" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-740">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-740">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-741">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.PropertyBatchResult" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-741">See <see cref="T:System.Fabric.PropertyBatchResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-742">Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-742">Either all or none of the operations in the batch will be committed.</span></span> </para>
          <para><span data-ttu-id="2cc07-743">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-743">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-744">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-744">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-745">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-745">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-746">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-746">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-747">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-747">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-748">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-748">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-749"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-749"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-750">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-750">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-751"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-751"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-752">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-752">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-753">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-753">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-754">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-754">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-755">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-755">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-756">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-756">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-757"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-757"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-758"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn der Eigenschaftswert größer als 1 MB ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-758"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when property value is larger than 1MB.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-759"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />wird zurückgegeben, wenn mindestens ein Vorgang in den Benutzer bereitgestellten <paramref name="operations" /> ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-759"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" /> is returned when at least one check operation in the user provided <paramref name="operations" /> has failed.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-760">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-760">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-761">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-761">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="SubmitPropertyBatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync (Uri parentName, System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; operations, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.PropertyBatchResult&gt; SubmitPropertyBatchAsync(class System.Uri parentName, class System.Collections.Generic.ICollection`1&lt;class System.Fabric.PropertyBatchOperation&gt; operations, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.PropertyManagementClient.SubmitPropertyBatchAsync(System.Uri,System.Collections.Generic.ICollection{System.Fabric.PropertyBatchOperation},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SubmitPropertyBatchAsync : Uri * System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;" Usage="propertyManagementClient.SubmitPropertyBatchAsync (parentName, operations, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.PropertyBatchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentName" Type="System.Uri" />
        <Parameter Name="operations" Type="System.Collections.Generic.ICollection&lt;System.Fabric.PropertyBatchOperation&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentName">
          <para><span data-ttu-id="2cc07-762">Der Name der übergeordneten Service Fabric unter dem die Eigenschaft Batchvorgänge ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-762">The parent Service Fabric name under which the Property batch operations will be executed.</span></span></para>
        </param>
        <param name="operations">
          <para><span data-ttu-id="2cc07-763">Die Eigenschaft Batchvorgänge.</span><span class="sxs-lookup"><span data-stu-id="2cc07-763">The batch property operations.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="2cc07-764">Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-764">The maximum amount of time the system will allow this operation to continue before returning <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="2cc07-765">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="2cc07-765">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="2cc07-766">Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="2cc07-766">It can be used to propagate notification that the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="2cc07-767">Übermittelt einen Befehlsbatch <see cref="T:System.Fabric.PropertyBatchOperation" />s.</span><span class="sxs-lookup"><span data-stu-id="2cc07-767">Submits a batch of <see cref="T:System.Fabric.PropertyBatchOperation" />s.</span></span> <span data-ttu-id="2cc07-768">Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-768">Either all or none of the operations in the batch will be committed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="2cc07-769">Eine Aufgabe, die den asynchronen Ladevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-769">A task that represents the asynchronous get operation.</span></span></para>
          <para><span data-ttu-id="2cc07-770">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.PropertyBatchResult" />.</span><span class="sxs-lookup"><span data-stu-id="2cc07-770">See <see cref="T:System.Fabric.PropertyBatchResult" />.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="2cc07-771">Entweder alle oder keiner der Vorgänge im Batch werden ein Commit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2cc07-771">Either all or none of the operations in the batch will be committed.</span></span> </para>
          <para><span data-ttu-id="2cc07-772">Timeout für den Vorgang wird auf Standard-Timeout (1 Minute) festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-772">Timeout for the operation will be set to default timeout (1 minute).</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="2cc07-773">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-773">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-774">E_INVALIDARG wird zurückgegeben, wenn ein oder mehrere Argumente ungültig sind.</span><span class="sxs-lookup"><span data-stu-id="2cc07-774">E_INVALIDARG is returned when one or more arguments are not valid.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="2cc07-775">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-775">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-776">E_POINTER wird zurückgegeben, wenn ein null-Verweis übergeben wird, eine Methode, die nicht als gültiges Argument akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="2cc07-776">E_POINTER is returned when a null reference is passed to a method that does not accept it as a valid argument.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para><span data-ttu-id="2cc07-777">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-777">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-778"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" />wird zurückgegeben, wenn vom Benutzer bereitgestellten <paramref name="parentName" /> ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="2cc07-778"><see cref="F:System.Fabric.FabricErrorCode.NameNotFound" /> is returned when the user provided <paramref name="parentName" /> does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para><span data-ttu-id="2cc07-779">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-779">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-780"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" />wird zurückgegeben, wenn dieser Schreibvorgang mit einem anderen Schreibvorgang in Konflikt steht.</span><span class="sxs-lookup"><span data-stu-id="2cc07-780"><see cref="F:System.Fabric.FabricErrorCode.WriteConflict" /> is returned when this write operation conflicts with another write operation.</span></span></para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para><span data-ttu-id="2cc07-781">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-781">Caused by one of the following:</span></span></para>
          <para><span data-ttu-id="2cc07-782">E_ABORT wird zurückgegeben, wenn der Vorgang abgebrochen wurde.</span><span class="sxs-lookup"><span data-stu-id="2cc07-782">E_ABORT is returned when operation was aborted.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="2cc07-783">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-783">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="2cc07-784">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="2cc07-784">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para><span data-ttu-id="2cc07-785">Durch eine der folgenden Ursachen:</span><span class="sxs-lookup"><span data-stu-id="2cc07-785">Caused by one of the following:</span></span></para>
          <para>
            <span data-ttu-id="2cc07-786"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />wird zurückgegeben, wenn <paramref name="parentName" /> ist kein gültiger Name Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="2cc07-786"><see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" /> is returned when <paramref name="parentName" /> is not a valid Service Fabric name.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-787"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" />wird zurückgegeben, wenn der Eigenschaftswert größer als 1 MB ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-787"><see cref="F:System.Fabric.FabricErrorCode.ValueTooLarge" /> is returned when property value is larger than 1MB.</span></span></para>
          <para>
            <span data-ttu-id="2cc07-788"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" />wird zurückgegeben, wenn mindestens ein Vorgang in den Benutzer bereitgestellten <paramref name="operations" /> ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="2cc07-788"><see cref="F:System.Fabric.FabricErrorCode.PropertyCheckFailed" /> is returned when at least one check operation in the user provided <paramref name="operations" /> has failed.</span></span></para>
          <para>
                <span data-ttu-id="2cc07-789">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="2cc07-789">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Runtime.InteropServices.COMException">
          <para><span data-ttu-id="2cc07-790">Diese Ausnahme wird ausgelöst, wenn ein interner Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2cc07-790">This exception is thrown when an internal error has occurred.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>