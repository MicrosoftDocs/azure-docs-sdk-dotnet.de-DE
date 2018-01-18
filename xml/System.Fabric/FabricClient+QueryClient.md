<Type Name="FabricClient+QueryClient" FullName="System.Fabric.FabricClient+QueryClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.QueryClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/QueryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.QueryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.QueryClient" />
  <TypeSignature Language="F#" Value="type FabricClient.QueryClient = class" />
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
      <para><span data-ttu-id="c85ad-101">Stellt den Fabric-Client, der zum Ausgeben von Abfragen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c85ad-101">Represents the fabric client that can be used to issue queries.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync () As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="c85ad-102">Ruft die Details für alle Anwendungen, die im System erstellten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-102">Gets the details for all applications created in the system.</span></span> <span data-ttu-id="c85ad-103">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-103">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-104">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-104">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-105">Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-105">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
          <para><span data-ttu-id="c85ad-106">Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-106">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-107">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-107">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-108">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-108">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-109">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-109">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-110">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-110">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync applicationNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-111">Der Name der Anwendung, die ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-111">The name of the application to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-112">Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-112">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="c85ad-113">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-113">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-114">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-114">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-115">Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-115">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="c85ad-116">Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-116">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-117">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-117">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-118">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-118">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-119">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-119">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-120">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-120">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationListAsync (applicationNameFilter As Uri, continuationToken As String) As Task(Of ApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-121">Der Name der Anwendung, die ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-121">The name of the application to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-122">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-122">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-123">Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-123">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="c85ad-124">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-124">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-125">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-125">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-126">Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-126">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="c85ad-127">Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-127">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-128">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-128">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-129">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-129">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-130">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-130">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-131">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-131">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-132">Der Name der Anwendung, die ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-132">The name of the application to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-133">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-133">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-134">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-134">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-135">Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-135">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="c85ad-136">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-136">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-137">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-137">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-138">Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-138">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="c85ad-139">Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-139">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-140">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-140">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-141">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-141">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-142">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-142">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync (Uri applicationNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationListAsync(class System.Uri applicationNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationListAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationListAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationListAsync (applicationNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-143">Der Name der Anwendung, die ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-143">The name of the application to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-144">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-144">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-145">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-145">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-146">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-146">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-147">Ruft die Details an, für alle Anwendungen oder für eine bestimmte Anwendung, die im System erstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-147">Gets the details for all applications or for a specific application created in the system.</span></span> <span data-ttu-id="c85ad-148">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-148">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-149">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-149">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-150">Die zurückgegebene Aufgabe enthält die Liste der Anwendungen als <see cref="T:System.Fabric.Query.ApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-150">The returned task contains the list of applications as <see cref="T:System.Fabric.Query.ApplicationList" />.</span></span></para>
          <para><span data-ttu-id="c85ad-151">Wenn den Namen der bereitgestellten Anwendung keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-151">If the provided application name has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-152">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-152">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-153">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-153">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-154">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-154">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationLoadInformationAsync (applicationName As String) As Task(Of ApplicationLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-155">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-155">The URI of the application instance name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-156">Ruft die Last Informationen zur angegebenen Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-156">Retrieves the load information of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-157">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-157">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-158">Die zurückgegebene Aufgabe enthält die Informationen von einer Anwendung als <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-158">The returned task contains the information of an application as <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-159">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-159">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="c85ad-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-160"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-161">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-161">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-162">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-162">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-163">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-163">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync (string applicationName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationLoadInformation&gt; GetApplicationLoadInformationAsync(string applicationName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;" Usage="queryClient.GetApplicationLoadInformationAsync (applicationName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-164">Der URI des Instanznamens Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-164">The URI of the application instance name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-165">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-165">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-166">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-166">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-167">Ruft die Last Informationen zur angegebenen Instanz ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-167">Retrieves the load information of the specified application instance.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-168">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-168">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-169">Die zurückgegebene Aufgabe enthält die Informationen von einer Anwendung als <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-169">The returned task contains the information of an application as <see cref="T:System.Fabric.Query.ApplicationLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-170">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-170">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <span data-ttu-id="c85ad-171"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: Die Anwendung ist nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-171"><see cref="F:System.Fabric.FabricErrorCode.ApplicationNotFound" />: The application does not exist.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-172">Das Zeitlimit der Anforderung wurde überschritten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-172">The request timed out.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-173">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-173">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationNameResult&gt; GetApplicationNameAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationNameAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationNameAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;" Usage="queryClient.GetApplicationNameAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-174">Der Name des Diensts, der den Anwendungsnamen für abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-174">The name of the service to get the application name for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-175">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-175">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-176">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-176">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-177">Ruft den Anwendungsnamen für den angegebenen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-177">Gets the application name for the specified service.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-178">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-178">A task that represents the asynchronous query operation.</span></span> </para>
          <para><span data-ttu-id="c85ad-179">Die zurückgegebene Aufgabe enthält den Anwendungsnamen als <see cref="T:System.Fabric.Query.ApplicationNameResult" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-179">The returned task contains the application name as <see cref="T:System.Fabric.Query.ApplicationNameResult" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-180">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-180">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-181">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-181">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-182">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-182">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync applicationQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><span data-ttu-id="c85ad-183">Die <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> , der bestimmt, welche Anwendungen abgefragt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-183">The <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> that determines which applications should be queried.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-184">Ruft die Details der Anwendungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-184">Gets the details of applications created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="c85ad-185">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-185">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-186">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-186">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="c85ad-187">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationList" /> , die die Liste der Anwendungen, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="c85ad-187">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationList" /> that represents the list of applications that respect the filters in the <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="c85ad-188">Wenn die Beschreibung der bereitgestellten Abfrage keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-188">If the provided query description has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-189">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-189">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-190">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-190">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-191">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-191">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationPagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync (System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationList&gt; GetApplicationPagedListAsync(class System.Fabric.Description.ApplicationQueryDescription applicationQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationPagedListAsync(System.Fabric.Description.ApplicationQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationPagedListAsync : System.Fabric.Description.ApplicationQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;" Usage="queryClient.GetApplicationPagedListAsync (applicationQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationQueryDescription" Type="System.Fabric.Description.ApplicationQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationQueryDescription">
          <para><span data-ttu-id="c85ad-192">Die <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> , der bestimmt, welche Anwendungen abgefragt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-192">The <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> that determines which applications should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-193">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-193">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-194">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-194">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-195">Ruft die Details der Anwendungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-195">Gets the details of applications created that match filters specified in query description (if any).</span></span>
            <span data-ttu-id="c85ad-196">Wenn die Anwendungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-196">If the applications do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-197">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-197">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span>
            <span data-ttu-id="c85ad-198">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationList" /> , die die Liste der Anwendungen, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="c85ad-198">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationList" /> that represents the list of applications that respect the filters in the <see cref="T:System.Fabric.Description.ApplicationQueryDescription" /> and fit the page.</span></span>
            <span data-ttu-id="c85ad-199">Wenn die Beschreibung der bereitgestellten Abfrage keine übereinstimmenden Anwendungen verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-199">If the provided query description has no matching applications, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-200">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-200">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-201">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-201">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-202">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-202">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync () As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c85ad-203">Ruft die Details für alle Anwendungstypen bereitgestellt oder im System bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-203">Gets the details for all the application types provisioned or being provisioned in the system.</span></span>
            <span data-ttu-id="c85ad-204">Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-204">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="c85ad-205">Diese Methode wird in der Zukunft als veraltet markiert.</span><span class="sxs-lookup"><span data-stu-id="c85ad-205">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-206">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-206">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-207">Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-207">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-208">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-208">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-209">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-209">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-210">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-210">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypeListAsync (applicationTypeNameFilter As String) As Task(Of ApplicationTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync applicationTypeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para><span data-ttu-id="c85ad-211">Der Typname der Anwendung zum Abrufen von Diensttypen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-211">The type name of the application to get service types for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-212">Ruft die Details für alle Anwendungstypen bereitgestellt oder im System oder für den angegebenen Anwendungstyp bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-212">Gets the details for all the application types provisioned or being provisioned in the system or for the specified application type.</span></span>
            <span data-ttu-id="c85ad-213">Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-213">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="c85ad-214">Diese Methode wird in der Zukunft als veraltet markiert.</span><span class="sxs-lookup"><span data-stu-id="c85ad-214">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-215">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-215">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-216">Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-216">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-217">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-217">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-218">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-218">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-219">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-219">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-220">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-220">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync (string applicationTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypeList&gt; GetApplicationTypeListAsync(string applicationTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;" Usage="queryClient.GetApplicationTypeListAsync (applicationTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeNameFilter">
          <para><span data-ttu-id="c85ad-221">Der Typname der Anwendung zum Abrufen von Diensttypen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-221">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-222">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-222">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-223">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-223">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-224">Ruft die Details für alle Anwendungstypen bereitgestellt oder im System oder für den angegebenen Anwendungstyp bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-224">Gets the details for all the application types provisioned or being provisioned in the system or for the specified application type.</span></span>
            <span data-ttu-id="c85ad-225">Verwenden Sie für weitere Funktionalität <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-225">For more functionality, please use <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span>
            <span data-ttu-id="c85ad-226">Diese Methode wird in der Zukunft als veraltet markiert.</span><span class="sxs-lookup"><span data-stu-id="c85ad-226">This method will be deprecated in the future.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-227">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-227">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-228">Die zurückgegebene Aufgabe enthält die Liste der Anwendungstypen als <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-228">The returned task contains the list of application types as <see cref="T:System.Fabric.Query.ApplicationTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-229">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-229">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-230">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-230">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-231">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-231">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync () As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
                    <span data-ttu-id="c85ad-232">Ruft die Details für alle Anwendungstypen bereitgestellt oder im System bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-232">Gets the details for all the application types provisioned or being provisioned in the system.</span></span> 
                </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="c85ad-233">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-233">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="c85ad-234">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-234">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="c85ad-235">Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-235">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-236">Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c85ad-236">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="c85ad-237">Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-237">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="c85ad-238">Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-238">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="c85ad-239">Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="c85ad-239">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="c85ad-240">Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="c85ad-240">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-241">Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-241">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-242">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-242">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-243">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-243">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-244">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-244">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetApplicationTypePagedListAsync (queryDescription As PagedApplicationTypeQueryDescription) As Task(Of ApplicationTypePagedList)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync queryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    <span data-ttu-id="c85ad-245">Ein <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> Objekt beschreibt, welche Anwendung Typen zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-245">A <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> object describing which application types to return.</span></span>
                    </para>
        </param>
        <summary>
          <para>
                    <span data-ttu-id="c85ad-246">Ruft die Details für Anwendungstypen bereitgestellt oder QueryDescription Arguments gebotenen bereitgestellt wird, in das System die Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-246">Gets the details for application types provisioned or being provisioned in the system which match filters provided by the queryDescription argument.</span></span>
                    </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="c85ad-247">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-247">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="c85ad-248">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-248">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="c85ad-249">Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-249">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-250">Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c85ad-250">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="c85ad-251">Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-251">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="c85ad-252">Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-252">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="c85ad-253">Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="c85ad-253">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="c85ad-254">Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="c85ad-254">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-255">Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-255">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-256">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-256">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-257">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-257">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-258">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-258">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetApplicationTypePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync (System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ApplicationTypePagedList&gt; GetApplicationTypePagedListAsync(class System.Fabric.Description.PagedApplicationTypeQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync(System.Fabric.Description.PagedApplicationTypeQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetApplicationTypePagedListAsync : System.Fabric.Description.PagedApplicationTypeQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;" Usage="queryClient.GetApplicationTypePagedListAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ApplicationTypePagedList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.PagedApplicationTypeQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para>
                    <span data-ttu-id="c85ad-259">Ein <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> Objekt beschreibt, welche Anwendung Typen zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-259">A <see cref="T:System.Fabric.Description.PagedApplicationTypeQueryDescription" /> object describing which application types to return.</span></span>
                    </para>
        </param>
        <param name="timeout">
          <para>
                    <span data-ttu-id="c85ad-260">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-260">Specifies the duration this operation has to complete before timing out.</span></span>
                </para>
        </param>
        <param name="cancellationToken">
          <para>
                    <span data-ttu-id="c85ad-261">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-261">Propagates notification that operations should be canceled.</span></span>
                </para>
        </param>
        <summary>
          <para>
                    <span data-ttu-id="c85ad-262">Ruft die Details für Anwendungstypen bereitgestellt oder QueryDescription Arguments gebotenen bereitgestellt wird, in das System die Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-262">Gets the details for application types provisioned or being provisioned in the system which match filters provided by the queryDescription argument.</span></span>
                    </para>
        </summary>
        <returns>
          <para>
                   <span data-ttu-id="c85ad-263">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-263">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="c85ad-264">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-264">The value of TResult parameter is an <see cref="T:System.Fabric.Query.ApplicationTypePagedList" />.</span></span>
                   </para>
          <para> 
                   <span data-ttu-id="c85ad-265">Wenn keine Anwendungstypen die bereitgestellten Filter entsprechen entsprechen, gibt diese Abfrage keine Anwendungstypen statt eines Fehlers an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-265">If no application types are found matching the filters provided, this query returns no application types rather than an error.</span></span>
                </para>
        </returns>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-266">Dies ist eine ausgelagerte Abfrage, d. h., wenn nicht alle Anwendungstypen in eine Seite passen wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken ausgegeben, die zum Abrufen der nächsten Seite verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c85ad-266">This is a paged query, meaning that if not all of the application types fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span> <span data-ttu-id="c85ad-267">Z. B. 10000 Anwendungstypen während eine Seite passt nur die ersten 3000 Anwendungstypen, wird 3000 zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-267">For example, if there are 10000 application types but a page only fits the first 3000 application types, 3000 is returned.</span></span>
                    <span data-ttu-id="c85ad-268">Wenn Sie auf den Rest der Ergebnisse zugreifen möchten, rufen Sie die anschließenden Seiten ab, indem Sie in der nächsten Abfrage das zurückgegebene Fortsetzungstoken verwenden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-268">To access the rest of the results, retrieve subsequent pages by using the returned continuation token in the next query.</span></span>
                    <span data-ttu-id="c85ad-269">Ein Fortsetzungstoken null wird zurückgegeben, wenn keine nachfolgenden Seiten vorhanden sind.</span><span class="sxs-lookup"><span data-stu-id="c85ad-269">A null continuation token is returned if there are no subsequent pages.</span></span>
                    </para>
          <para>
                    <span data-ttu-id="c85ad-270">Jede Version einen bestimmten Anwendungstyp ist ein Eintrag in das Ergebnis.</span><span class="sxs-lookup"><span data-stu-id="c85ad-270">Each version of a particular application type is one entry in the result.</span></span>
                </para>
        </remarks>
        <remarks>
          <para>
                    <span data-ttu-id="c85ad-271">Weitere Details zu den hier Anwendungstypen anzuzeigen: <see cref="T:System.Fabric.Query.ApplicationType" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-271">See more details about application types here: <see cref="T:System.Fabric.Query.ApplicationType" />.</span></span>
                </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-272">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-272">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-273">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-273">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-274">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-274">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterLoadInformationAsync () As Task(Of ClusterLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c85ad-275">Ruft die Clusterinformationen für den Auslastungstest an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-275">Gets the cluster load information.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-276">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-276">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-277">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-277">See <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
          <para><span data-ttu-id="c85ad-278">Die zurückgegebene Aufgabe enthält die Informationen zum Laden der Cluster als <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-278">The returned task contains the load information of the cluster as <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-279">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-279">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-280">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-280">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-281">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-281">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-282">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-282">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ClusterLoadInformation&gt; GetClusterLoadInformationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetClusterLoadInformationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterLoadInformationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;" Usage="queryClient.GetClusterLoadInformationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ClusterLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-283">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-283">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-284">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-284">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-285">Ruft die Clusterinformationen für den Auslastungstest an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-285">Gets the cluster load information.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-286">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-286">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-287">Die zurückgegebene Aufgabe enthält die Informationen zum Laden der Cluster als <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-287">The returned task contains the load information of the cluster as <see cref="T:System.Fabric.Query.ClusterLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-288">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-288">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-289">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-289">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-290">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-290">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-291">Der Name des Knotens für Anwendungen abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-291">The name of the node to get applications for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-292">Ruft die Liste der bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-292">Gets the deployed application list.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-293">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-293">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-294">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-294">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-295">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-295">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-296">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-296">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-297">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-297">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-298">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-298">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedApplicationListAsync (nodeName As String, applicationNameFilter As Uri) As Task(Of DeployedApplicationList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-299">Der Name des Knotens für Anwendungen abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-299">The name of the node to get applications for.</span></span></para>
        </param>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-300">Filtern Sie die Ergebnisse, um nur Anwendungen, die entsprechend den Anwendungsnamen gehören.</span><span class="sxs-lookup"><span data-stu-id="c85ad-300">Filter results to include only applications matching this application name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-301">Ruft die bereitgestellte Anwendungen auf einem Knoten mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-301">Gets the deployed applications on a node with the specified application name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-302">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-302">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-303">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-303">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-304">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-304">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-305">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-305">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-306">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-306">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-307">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-307">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedApplicationListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync (string nodeName, Uri applicationNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedApplicationList&gt; GetDeployedApplicationListAsync(string nodeName, class System.Uri applicationNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedApplicationListAsync(System.String,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedApplicationListAsync : string * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;" Usage="queryClient.GetDeployedApplicationListAsync (nodeName, applicationNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedApplicationList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-308">Der Name des Knotens für Anwendungen abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-308">The name of the node to get applications for.</span></span></para>
        </param>
        <param name="applicationNameFilter">
          <para><span data-ttu-id="c85ad-309">Filtern Sie die Ergebnisse, um nur Anwendungen, die entsprechend den Anwendungsnamen gehören.</span><span class="sxs-lookup"><span data-stu-id="c85ad-309">Filter results to include only applications matching this application name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-310">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-310">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-311">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-311">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-312">Ruft die bereitgestellte Anwendungen auf einem Knoten mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-312">Gets the deployed applications on a node with the specified application name.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-313">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-313">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-314">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Anwendungen als <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-314">The returned task contains the list of deployed applications as <see cref="T:System.Fabric.Query.DeployedApplicationList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-315">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-315">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-316">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-316">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-317">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-317">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-318">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-318">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-319">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-319">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-320">Ruft die Liste der bereitgestellten Code-Pakete.</span><span class="sxs-lookup"><span data-stu-id="c85ad-320">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-321">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-321">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-322">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-322">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-323">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-323">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-324">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-324">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-325">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-325">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-326">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-326">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedCodePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, codePackageNameFilter As String) As Task(Of DeployedCodePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-327">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-327">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-328">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-328">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-329">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-329">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="codePackageNameFilter">
          <para><span data-ttu-id="c85ad-330">Filtern Sie die Ergebnisse, um nur die passenden dieser codepaketname enthalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-330">Filter results to include only those matching this code package name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-331">Ruft die Liste der bereitgestellten Code-Pakete.</span><span class="sxs-lookup"><span data-stu-id="c85ad-331">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-332">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-332">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-333">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-333">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-334">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-334">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-335">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-335">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-336">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-336">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-337">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-337">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedCodePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedCodePackageList&gt; GetDeployedCodePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string codePackageNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedCodePackageListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedCodePackageListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;" Usage="queryClient.GetDeployedCodePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, codePackageNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedCodePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="codePackageNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-338">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-338">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-339">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-339">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-340">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-340">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="codePackageNameFilter">
          <para><span data-ttu-id="c85ad-341">Filtern Sie die Ergebnisse, um nur die passenden dieser codepaketname enthalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-341">Filter results to include only those matching this code package name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-342">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-342">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-343">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-343">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-344">Ruft die Liste der bereitgestellten Code-Pakete.</span><span class="sxs-lookup"><span data-stu-id="c85ad-344">Gets the list of the deployed code packages.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-345">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-345">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-346">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Code-Pakete als <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-346">The returned task contains the list of deployed code packages as <see cref="T:System.Fabric.Query.DeployedCodePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-347">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-347">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-348">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-348">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-349">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-349">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaDetailAsync (nodeName As String, partitionId As Guid, replicaId As Long) As Task(Of DeployedServiceReplicaDetail)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-350">Der Knotenname, von dem die Ergebnisse gewünscht sind.</span><span class="sxs-lookup"><span data-stu-id="c85ad-350">The node name from which the results are desired.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-351">Die Partitions-Id für die die Ergebnisse gewünscht werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-351">The partition id for which the results are desired.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="c85ad-352">Der Bezeichner für das Replikat oder die Instanz, für die die Ergebnisse gewünscht werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-352">The identifier for the replica or the instance for which the results are desired.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-353">Gibt die Details eines Replikats auf dem angegebenen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-353">Returns details of a replica running on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-354">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-354">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-355">Die zurückgegebene Aufgabe enthält die Replikatinformationen als <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-355">The returned task contains the replica information as <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-356">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-356">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-357">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-357">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-358">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-358">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-359">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-359">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-360">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-360">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-361">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-361">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaDetailAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync (string nodeName, Guid partitionId, long replicaId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaDetail&gt; GetDeployedReplicaDetailAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaDetailAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;" Usage="queryClient.GetDeployedReplicaDetailAsync (nodeName, partitionId, replicaId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-362">Der Knotenname, von dem die Ergebnisse gewünscht sind.</span><span class="sxs-lookup"><span data-stu-id="c85ad-362">The node name from which the results are desired.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-363">Die Partitions-Id für die die Ergebnisse gewünscht werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-363">The partition id for which the results are desired.</span></span></para>
        </param>
        <param name="replicaId">
          <para><span data-ttu-id="c85ad-364">Der Bezeichner für das Replikat oder die Instanz, für die die Ergebnisse gewünscht werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-364">The identifier for the replica or the instance for which the results are desired.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-365">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-365">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-366">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-366">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-367">Gibt die Details eines Replikats auf dem angegebenen Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-367">Returns details of a replica running on the specified node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-368">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-368">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-369">Die zurückgegebene Aufgabe enthält die Replikatinformationen als <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-369">The returned task contains the replica information as <see cref="T:System.Fabric.Query.DeployedServiceReplicaDetail" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-370">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-370">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-371">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-371">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-372">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-372">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-373">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-373">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-374">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-374">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-375">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-375">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-376">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-376">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-377">Ruft die Ansicht der Replikate von einem Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-377">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-378">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-378">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-379">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-379">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-380">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-380">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-381">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-381">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-382">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-382">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-383">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-383">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-384">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-384">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-385">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-385">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-386">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-386">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-387">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-387">The name of the application.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-388">Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</span><span class="sxs-lookup"><span data-stu-id="c85ad-388">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-389">Ruft die Ansicht der Replikate von einem Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-389">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-390">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-390">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-391">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-391">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-392">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-392">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-393">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-393">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-394">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-394">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-395">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-395">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-396">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-396">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-397">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-397">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedReplicaListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, partitionIdFilter As Nullable(Of Guid)) As Task(Of DeployedServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-398">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-398">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-399">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-399">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-400">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-400">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-401">Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</span><span class="sxs-lookup"><span data-stu-id="c85ad-401">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-402">Ruft die Ansicht der Replikate von einem Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-402">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-403">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-403">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-404">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-404">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-405">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-405">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-406">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-406">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-407">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-407">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-408">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-408">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-409">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-409">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-410">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-410">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceReplicaList&gt; GetDeployedReplicaListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri,System.String,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedReplicaListAsync : string * Uri * string * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;" Usage="queryClient.GetDeployedReplicaListAsync (nodeName, applicationName, serviceManifestNameFilter, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-411">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-411">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-412">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-412">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-413">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-413">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-414">Filtern Sie, sodass Sie Ergebnisse nur Replikate, die mit dieser ID der Partition enthalten</span><span class="sxs-lookup"><span data-stu-id="c85ad-414">Filter results to only include replicas matching this partition ID.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-415">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-415">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-416">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c85ad-416">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="c85ad-417">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-417">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="c85ad-418">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-418">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-419">Ruft die Ansicht der Replikate von einem Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-419">Gets the view of replicas from a node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-420">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-420">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-421">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstreplikate als <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-421">The returned task contains the list of deployed service replicas as <see cref="T:System.Fabric.Query.DeployedServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-422">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-422">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-423">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-423">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-424">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-424">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-425">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-425">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-426">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-426">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-427">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-427">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-428">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-428">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-429">Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-429">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-430">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-430">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-431">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-431">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-432">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-432">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-433">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-433">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-434">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-434">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-435">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-435">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServicePackageListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String) As Task(Of DeployedServicePackageList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-436">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-436">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-437">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-437">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-438">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-438">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-439">Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-439">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-440">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-440">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-441">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-441">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-442">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-442">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-443">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-443">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-444">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-444">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-445">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-445">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServicePackageListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServicePackageList&gt; GetDeployedServicePackageListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServicePackageListAsync : string * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;" Usage="queryClient.GetDeployedServicePackageListAsync (nodeName, applicationName, serviceManifestNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServicePackageList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-446">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-446">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-447">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-447">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-448">Filtern Sie die Ergebnisse umfassen nur die diesem Dienst passenden Namen manifest.</span><span class="sxs-lookup"><span data-stu-id="c85ad-448">Filter results to include only those matching this service manifest name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-449">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-449">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-450">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-450">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-451">Ruft die bereitgestellten dienstpakete für die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-451">Gets the deployed service packages for the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-452">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-452">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-453">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten dienstpakete als <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-453">The returned task contains the list of deployed service packages as <see cref="T:System.Fabric.Query.DeployedServicePackageList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-454">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-454">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-455">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-455">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-456">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-456">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-457">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-457">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-458">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-458">The name of the application.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-459">Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-459">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-460">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-460">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-461">Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-461">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-462">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-462">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-463">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-463">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-464">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-464">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-465">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-465">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetDeployedServiceTypeListAsync (nodeName As String, applicationName As Uri, serviceManifestNameFilter As String, serviceTypeNameFilter As String) As Task(Of DeployedServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-466">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-466">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-467">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-467">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-468">Filtern Sie die Ergebnisse, um nur die übereinstimmenden dieser dienstmanifestname Diensttypen enthalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-468">Filter results to include only service types matching this service manifest name.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="c85ad-469">Filtern Sie die Ergebnisse umfassen nur die Diensttypen, die mit diesem Namen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-469">Filter results to include only service types matching this name.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-470">Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-470">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-471">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-471">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-472">Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-472">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-473">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-473">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-474">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-474">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-475">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-475">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-476">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-476">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetDeployedServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync (string nodeName, Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.DeployedServiceTypeList&gt; GetDeployedServiceTypeListAsync(string nodeName, class System.Uri applicationName, string serviceManifestNameFilter, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetDeployedServiceTypeListAsync(System.String,System.Uri,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetDeployedServiceTypeListAsync : string * Uri * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;" Usage="queryClient.GetDeployedServiceTypeListAsync (nodeName, applicationName, serviceManifestNameFilter, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.DeployedServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceManifestNameFilter" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-477">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-477">The name of the node.</span></span></para>
        </param>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-478">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-478">The name of the application.</span></span></para>
        </param>
        <param name="serviceManifestNameFilter">
          <para><span data-ttu-id="c85ad-479">Filtern Sie die Ergebnisse, um nur die übereinstimmenden dieser dienstmanifestname Diensttypen enthalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-479">Filter results to include only service types matching this service manifest name.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="c85ad-480">Filtern Sie die Ergebnisse umfassen nur die Diensttypen, die mit diesem Namen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-480">Filter results to include only service types matching this name.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-481">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-481">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-482">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-482">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-483">Ruft die bereitgestellte Diensttypen auf die angegebenen Knoten und die Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-483">Gets the deployed service types on the given node and application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-484">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-484">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-485">Die zurückgegebene Aufgabe enthält die Liste der Typen als bereitgestellten Dienste <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-485">The returned task contains the list of deployed service types as <see cref="T:System.Fabric.Query.DeployedServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-486">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-486">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-487">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-487">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-488">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-488">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync () As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="c85ad-489">Ruft die Details für alle Knoten im Cluster ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-489">Gets the details for all nodes in the cluster.</span></span> <span data-ttu-id="c85ad-490">Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-490">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-491">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-491">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-492">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-492">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-493">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-493">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-494">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-494">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-495">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-495">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync nodeNameFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="c85ad-496">Der Name des Knotens für Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-496">The name of the node to get details for.</span></span> <span data-ttu-id="c85ad-497">Der Name des Knotens wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-497">The node name is case-insensitive.</span></span> <span data-ttu-id="c85ad-498">Ruft alle Knoten im Cluster an, wenn der Name des angegebenen Knotens null ist.</span><span class="sxs-lookup"><span data-stu-id="c85ad-498">Gets all nodes in the cluster if the given node name is null.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-499">Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-499">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="c85ad-500">Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-500">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-501">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-501">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-502">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-502">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-503">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-503">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-504">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-504">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-505">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-505">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-506">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-506">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeListAsync (nodeNameFilter As String, continuationToken As String) As Task(Of NodeList)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="c85ad-507">Der Name des Knotens für Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-507">The name of the node to get details for.</span></span> <span data-ttu-id="c85ad-508">Der Name des Knotens wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-508">The node name is case-insensitive.</span></span> <span data-ttu-id="c85ad-509">Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</span><span class="sxs-lookup"><span data-stu-id="c85ad-509">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-510">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-510">The continuation token obtained from a previous query.</span></span></para>
          <returns>
            <para><span data-ttu-id="c85ad-511">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-511">A task that represents the asynchronous query operation.</span></span></para>
            <para><span data-ttu-id="c85ad-512">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-512">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
          </returns>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-513">Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-513">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="c85ad-514">Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-514">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-515">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-515">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-516">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-516">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-517">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-517">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-518">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-518">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="c85ad-519">Der Name des Knotens für Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-519">The name of the node to get details for.</span></span> <span data-ttu-id="c85ad-520">Der Name des Knotens wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-520">The node name is case-insensitive.</span></span> <span data-ttu-id="c85ad-521">Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</span><span class="sxs-lookup"><span data-stu-id="c85ad-521">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-522">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-522">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-523">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-523">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-524">Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-524">Gets the details for all nodes in the cluster or for the specified node.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-525">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-525">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-526">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-526">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-527">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-527">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-528">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-528">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-529">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-529">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="c85ad-530">Der Name des Knotens für Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-530">The name of the node to get details for.</span></span> <span data-ttu-id="c85ad-531">Der Name des Knotens wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-531">The node name is case-insensitive.</span></span> <span data-ttu-id="c85ad-532">Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</span><span class="sxs-lookup"><span data-stu-id="c85ad-532">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-533">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-533">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-534">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-534">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-535">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-535">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-536">Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-536">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="c85ad-537">Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-537">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-538">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-538">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-539">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-539">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-540">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-540">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-541">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-541">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-542">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-542">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt; GetNodeListAsync (string nodeNameFilter, System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeList&gt; GetNodeListAsync(string nodeNameFilter, valuetype System.Fabric.Query.NodeStatusFilter nodeStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync(System.String,System.Fabric.Query.NodeStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeListAsync : string * System.Fabric.Query.NodeStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;" Usage="queryClient.GetNodeListAsync (nodeNameFilter, nodeStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeNameFilter" Type="System.String" />
        <Parameter Name="nodeStatusFilter" Type="System.Fabric.Query.NodeStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeNameFilter">
          <para><span data-ttu-id="c85ad-543">Der Name des Knotens für Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-543">The name of the node to get details for.</span></span> <span data-ttu-id="c85ad-544">Der Name des Knotens wird die Groß-/Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-544">The node name is case-insensitive.</span></span> <span data-ttu-id="c85ad-545">Ruft alle Knoten ab, wenn der Name des angegebenen Knotens null ist.</span><span class="sxs-lookup"><span data-stu-id="c85ad-545">Gets all nodes if the given node name is null.</span></span></para>
        </param>
        <param name="nodeStatusFilter">
          <para><span data-ttu-id="c85ad-546">Der Knoten status(es) der Knoten, um ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-546">The node status(es) of the nodes to get details for.</span></span></para>
        </param>
        <param name="continuationToken"><span data-ttu-id="c85ad-547">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-547">The continuation token obtained from a previous query.</span></span></param>
        <param name="timeout"><span data-ttu-id="c85ad-548">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-548">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c85ad-549">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-549">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
            <span data-ttu-id="c85ad-550">Ruft Sie die Details für alle Knoten im Cluster oder für den angegebenen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-550">Gets the details for all nodes in the cluster or for the specified node.</span></span> <span data-ttu-id="c85ad-551">Wenn der Knoten nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-551">If the nodes do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </summary>
        <returns>
          <para><span data-ttu-id="c85ad-552">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-552">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-553">Die zurückgegebene Aufgabe enthält die Liste der Knoten als <see cref="T:System.Fabric.Query.NodeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-553">The returned task contains the list of nodes as <see cref="T:System.Fabric.Query.NodeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-554">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-554">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-555">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-555">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-556">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-556">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNodeLoadInformationAsync (nodeName As String) As Task(Of NodeLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-557">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-557">The name of the node.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-558">Abrufen von Metriken und Informationen auf dem Knoten geladen werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-558">Get metrics and load information on the node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-559">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-559">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-560">Die zurückgegebene Aufgabe enthält die Informationen des Knotens als <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-560">The returned task contains the load information of the node as <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-561">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-561">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-562">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-562">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-563">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-563">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-564">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-564">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetNodeLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.NodeLoadInformation&gt; GetNodeLoadInformationAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetNodeLoadInformationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetNodeLoadInformationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;" Usage="queryClient.GetNodeLoadInformationAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.NodeLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="c85ad-565">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="c85ad-565">The name of the node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-566">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-566">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-567">Verteilt die Benachrichtigung, dass Vorgänge abgebrochen werden sollen</span><span class="sxs-lookup"><span data-stu-id="c85ad-567">Propagates notification that operations should be canceled</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-568">Abrufen von Metriken und Informationen auf dem Knoten geladen werden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-568">Get metrics and load information on the node.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-569">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-569">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-570">Die zurückgegebene Aufgabe enthält die Informationen des Knotens als <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-570">The returned task contains the load information of the node as <see cref="T:System.Fabric.Query.NodeLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-571">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-571">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-572">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-572">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-573">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-573">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionAsync (partitionId As Guid) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-574">Die Partitions-ID der Partition zum Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="c85ad-574">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-575">Ruft die Details für die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-575">Gets the details for the specified partition.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-576">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-576">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-577">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-577">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-578">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-578">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-579">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-579">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-580">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-580">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-581">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-581">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-582">Die Partitions-ID der Partition zum Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="c85ad-582">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-583">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-583">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-584">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-584">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-585">Ruft die Details für die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-585">Gets the details for the specified partition.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-586">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-586">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-587">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-587">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-588">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-588">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-589">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-589">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-590">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-590">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-591">Der Name des Diensts zum Abrufen von Partitionen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-591">The name of the service to get partitions for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-592">Ruft die Details für alle Partitionen eines Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-592">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="c85ad-593">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-593">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-594">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-594">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-595">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-595">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-596">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-596">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-597">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-597">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-598">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-598">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-599">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-599">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, partitionIdFilter As Nullable(Of Guid)) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-600">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-600">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-601">Die Partitions-ID der Partition zum Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="c85ad-601">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-602">Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-602">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="c85ad-603">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-603">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-604">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-604">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-605">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-605">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-606">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-606">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-607">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-607">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-608">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-608">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-609">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-609">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionListAsync (serviceName As Uri, continuationToken As String) As Task(Of ServicePartitionList)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-610">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-610">The name of the service.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-611">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-611">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-612">Ruft die Details für alle Partitionen eines Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-612">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="c85ad-613">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-613">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-614">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-614">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-615">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-615">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-616">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-616">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-617">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-617">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-618">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-618">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-619">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-619">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-620">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-620">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-621">Die Partitions-ID der Partition zum Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="c85ad-621">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-622">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-622">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-623">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-623">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-624">Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-624">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="c85ad-625">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-625">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-626">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-626">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-627">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-627">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-628">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-628">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-629">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-629">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-630">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-630">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync (Uri serviceName, Nullable&lt;Guid&gt; partitionIdFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServicePartitionList&gt; GetPartitionListAsync(class System.Uri serviceName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; partitionIdFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionListAsync(System.Uri,System.Nullable{System.Guid},System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionListAsync : Uri * Nullable&lt;Guid&gt; * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;" Usage="queryClient.GetPartitionListAsync (serviceName, partitionIdFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServicePartitionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionIdFilter" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-631">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-631">The name of the service.</span></span></para>
        </param>
        <param name="partitionIdFilter">
          <para><span data-ttu-id="c85ad-632">Die Partitions-ID der Partition zum Abrufen von Details.</span><span class="sxs-lookup"><span data-stu-id="c85ad-632">The partition ID of the partition to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-633">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-633">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-634">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-634">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-635">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-635">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-636">Ruft die Details für alle Partitionen eines Diensts oder nur die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-636">Gets the details for all partitions of a service or just the specified partition.</span></span> <span data-ttu-id="c85ad-637">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-637">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-638">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-638">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-639">Die zurückgegebene Aufgabe enthält die Liste der Partitionen als <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-639">The returned task contains the list of partitions as <see cref="T:System.Fabric.Query.ServicePartitionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-640">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-640">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-641">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-641">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-642">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-642">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPartitionLoadInformationAsync (partitionId As Guid) As Task(Of PartitionLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-643">Die Partitions-ID der Partition zum Abrufen von Informationen für geladen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-643">The partition ID of the partition to get load information for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-644">Ruft die Informationen über die Auslastung der Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-644">Gets the information about the partition load.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-645">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-645">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-646">Die zurückgegebene Aufgabe enthält die Informationen zum Laden einer Partition als <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-646">The returned task contains the load information of a partition as <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-647">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-647">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-648">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-648">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-649">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-649">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-650">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-650">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.PartitionLoadInformation&gt; GetPartitionLoadInformationAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetPartitionLoadInformationAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetPartitionLoadInformationAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;" Usage="queryClient.GetPartitionLoadInformationAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.PartitionLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-651">Die Partitions-ID der Partition zum Abrufen von Informationen für geladen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-651">The partition ID of the partition to get load information for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-652">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-652">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-653">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-653">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-654">Ruft die Informationen über die Auslastung der Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-654">Gets the information about the partition load.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-655">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-655">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-656">Die zurückgegebene Aufgabe enthält die Informationen zum Laden einer Partition als <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-656">The returned task contains the load information of a partition as <see cref="T:System.Fabric.Query.PartitionLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-657">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-657">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-658">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-658">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-659">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-659">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync () As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c85ad-660">Ruft Details für alle Versionen des Cluster-Code im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-660">Gets details for all cluster code versions provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-661">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-661">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-662">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-662">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-663">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-663">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-664">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-664">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-665">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-665">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricCodeVersionListAsync (codeVersionFilter As String) As Task(Of ProvisionedFabricCodeVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync codeVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para><span data-ttu-id="c85ad-666">Die Codeversion zum Abrufen der Details für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-666">The code version to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-667">Ruft Details für den bestimmten Cluster Codeversion im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-667">Gets details for the specific cluster code version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-668">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-668">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-669">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-669">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-670">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-670">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-671">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-671">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-672">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-672">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-673">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-673">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricCodeVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync (string codeVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricCodeVersionList&gt; GetProvisionedFabricCodeVersionListAsync(string codeVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricCodeVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricCodeVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;" Usage="queryClient.GetProvisionedFabricCodeVersionListAsync (codeVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricCodeVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersionFilter">
          <para><span data-ttu-id="c85ad-674">Codeversion, die ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-674">Code version to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-675">Die maximale Zeitspanne für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-675">The maximum time allowed for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-676">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="c85ad-676">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-677">Ruft Details für den bestimmten Cluster Codeversion im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-677">Gets details for the specific cluster code version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-678">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-678">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-679">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Versionen der Service Fabric-Code als <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-679">The returned task contains the list of provisioned Service Fabric code versions as <see cref="T:System.Fabric.Query.ProvisionedFabricCodeVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-680">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-680">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-681">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-681">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-682">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-682">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync () As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="c85ad-683">Ruft Details für alle Cluster-Config-Versionen, die im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-683">Gets details for all cluster config versions provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-684">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-684">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-685">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-685">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-686">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-686">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-687">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-687">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-688">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-688">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetProvisionedFabricConfigVersionListAsync (configVersionFilter As String) As Task(Of ProvisionedFabricConfigVersionList)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync configVersionFilter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para><span data-ttu-id="c85ad-689">Zum Abrufen der Details für die Config-Version.</span><span class="sxs-lookup"><span data-stu-id="c85ad-689">The config version to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-690">Ruft Details für einen bestimmten Cluster Config-Version, die im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-690">Gets details for a specific cluster config version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-691">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-691">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-692">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-692">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-693">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-693">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-694">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-694">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-695">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-695">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-696">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-696">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetProvisionedFabricConfigVersionListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync (string configVersionFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ProvisionedFabricConfigVersionList&gt; GetProvisionedFabricConfigVersionListAsync(string configVersionFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetProvisionedFabricConfigVersionListAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetProvisionedFabricConfigVersionListAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;" Usage="queryClient.GetProvisionedFabricConfigVersionListAsync (configVersionFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ProvisionedFabricConfigVersionList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configVersionFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configVersionFilter">
          <para><span data-ttu-id="c85ad-697">Zum Abrufen der Details für die Config-Version.</span><span class="sxs-lookup"><span data-stu-id="c85ad-697">The config version to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-698">Die maximale Zeitspanne für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="c85ad-698">The maximum time allowed for the operation to complete before TimeoutException is thrown.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-699">Für zukünftige Verwendung reserviert.</span><span class="sxs-lookup"><span data-stu-id="c85ad-699">Reserved for future use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-700">Ruft Details für einen bestimmten Cluster Config-Version, die im System bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-700">Gets details for a specific cluster config version provisioned in the system.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-701">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-701">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-702">Die zurückgegebene Aufgabe enthält die Liste der bereitgestellten Service Fabric Config-Versionen als <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-702">The returned task contains the list of provisioned Service Fabric config versions as <see cref="T:System.Fabric.Query.ProvisionedFabricConfigVersionList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-703">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-703">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-704">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-704">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-705">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-705">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-706">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-706">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-707">Ruft die Details für alle Replikate einer Partition an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-707">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="c85ad-708">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-708">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-709">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-709">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-710">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-710">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-711">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-711">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-712">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-712">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-713">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-713">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-714">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-714">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-715">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-715">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, replicaIdOrInstanceIdFilter As Long) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-716">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-716">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="c85ad-717">Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-717">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-718">Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-718">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="c85ad-719">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-719">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-720">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-720">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-721">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-721">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-722">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-722">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-723">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-723">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-724">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-724">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-725">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-725">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-726">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-726">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-727">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-727">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaListAsync (partitionId As Guid, continuationToken As String) As Task(Of ServiceReplicaList)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-728">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-728">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-729">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-729">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-730">Ruft die Details für alle Replikate einer Partition an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-730">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="c85ad-731">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-731">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-732">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-732">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-733">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-733">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-734">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-734">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-735">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-735">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-736">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-736">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-737">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-737">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-738">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-738">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-739">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-739">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-740">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-740">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="c85ad-741">Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-741">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-742">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-742">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-743">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-743">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-744">Ruft die Details für alle Replikate einer Partition, die mit den Replikaten bzw. Instanzen Filter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-744">Gets the details for all replicas of a partition that match the replica or instance filter.</span></span> <span data-ttu-id="c85ad-745">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-745">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-746">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-746">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-747">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-747">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-748">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-748">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-749">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-749">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-750">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-750">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-751">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-751">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-752">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-752">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-753">Der Partitionsbezeichner der Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-753">The partition identifier of the partition to get replicas for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-754">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-754">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-755">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-755">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-756">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-756">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-757">Ruft die Details für alle Replikate einer Partition an.</span><span class="sxs-lookup"><span data-stu-id="c85ad-757">Gets the details for all replicas of a partition.</span></span> <span data-ttu-id="c85ad-758">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-758">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-759">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-759">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-760">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-760">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-761">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-761">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-762">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-762">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-763">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-763">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-764">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-764">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-765">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-765">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-766">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-766">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="c85ad-767">Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-767">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="replicaStatusFilter">
          <para><span data-ttu-id="c85ad-768">Das Replikat status(es) Replikate für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-768">The replica status(es) to get replicas for.</span></span></para>
        </param>
        <param name="timeout"><span data-ttu-id="c85ad-769">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-769">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c85ad-770">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-770">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-771">Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-771">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="c85ad-772">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-772">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-773">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-773">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-774">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-774">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-775">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-775">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-776">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-776">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-777">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-777">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-778">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-778">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-779">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-779">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync (Guid partitionId, long replicaIdOrInstanceIdFilter, System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceReplicaList&gt; GetReplicaListAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceIdFilter, valuetype System.Fabric.Query.ServiceReplicaStatusFilter replicaStatusFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaListAsync(System.Guid,System.Int64,System.Fabric.Query.ServiceReplicaStatusFilter,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaListAsync : Guid * int64 * System.Fabric.Query.ServiceReplicaStatusFilter * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;" Usage="queryClient.GetReplicaListAsync (partitionId, replicaIdOrInstanceIdFilter, replicaStatusFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceReplicaList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceIdFilter" Type="System.Int64" />
        <Parameter Name="replicaStatusFilter" Type="System.Fabric.Query.ServiceReplicaStatusFilter" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-780">Der Partitionsbezeichner für die Partition zum Abrufen von Replikaten für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-780">The partition identifier for the partition to get replicas for.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceIdFilter">
          <para><span data-ttu-id="c85ad-781">Der Replikat-ID oder Instanzbezeichner Replikate für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-781">The replica identifier or instance identifier to get replicas for.</span></span></para>
        </param>
        <param name="replicaStatusFilter">
          <para><span data-ttu-id="c85ad-782">Filtern Sie die Ergebnisse, um nur die passenden dieser Status des Replikats einschließen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-782">Filter results to include only those matching this replica status.</span></span></para>
        </param>
        <param name="continuationToken"><span data-ttu-id="c85ad-783">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-783">The continuation token obtained from a previous query.</span></span></param>
        <param name="timeout"><span data-ttu-id="c85ad-784">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-784">Specifies the duration this operation has to complete before timing out.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="c85ad-785">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-785">Propagates notification that operation should be canceled.</span></span></param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-786">Ruft die Details für alle Replikate einer Partition, die das Replikat oder Instanz Filter und dem Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-786">Gets the details for all replicas of a partition that match the replica or instance filter and the status filter.</span></span> <span data-ttu-id="c85ad-787">Wenn die Replikate nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-787">If the replicas do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-788">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-788">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-789">Die zurückgegebene Aufgabe enthält die Replikatinformationen der Partition als <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-789">The returned task contains the replica information of the partition as <see cref="T:System.Fabric.Query.ServiceReplicaList" />.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="c85ad-790">Service Fabric ist ein verteiltes System, auf dem verfügen viele Komponenten über eines Überblick über die gleiche Entität.</span><span class="sxs-lookup"><span data-stu-id="c85ad-790">Service Fabric is a distributed system where many components have a view of the same entity.</span></span> </para>
          <para>
                <span data-ttu-id="c85ad-791">Weist einen instabilen oder vorübergehender in dieser Ansicht entspricht möglicherweise nicht <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> und<see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span><span class="sxs-lookup"><span data-stu-id="c85ad-791">In an unstable or transient state, this view may not match <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaListAsync(System.String,System.Uri)" /> and <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedReplicaDetailAsync(System.String,System.Guid,System.Int64)" /></span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-792">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-792">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-793">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-793">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-794">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-794">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetReplicaLoadInformationAsync (partitionId As Guid, replicaIdOrInstanceId As Long) As Task(Of ReplicaLoadInformation)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-795">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="c85ad-795">The partition ID.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para><span data-ttu-id="c85ad-796">Der Replikat-ID (stateful Service) oder die Instanz-ID (statusfreien Dienst).</span><span class="sxs-lookup"><span data-stu-id="c85ad-796">The replica ID (stateful service) or instance ID (stateless service).</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-797">Erhalten Sie eine Liste der Metrik und ihre Arbeitslast auf einem Replikat aus.</span><span class="sxs-lookup"><span data-stu-id="c85ad-797">Get a list of metric and their load on a replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-798">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-798">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-799">Die zurückgegebene Aufgabe enthält die Informationen Laden des Replikats <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-799">The returned task contains the load information of the replica as <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-800">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-800">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-801">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-801">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-802">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-802">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-803">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-803">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetReplicaLoadInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync (Guid partitionId, long replicaIdOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ReplicaLoadInformation&gt; GetReplicaLoadInformationAsync(valuetype System.Guid partitionId, int64 replicaIdOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetReplicaLoadInformationAsync(System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetReplicaLoadInformationAsync : Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;" Usage="queryClient.GetReplicaLoadInformationAsync (partitionId, replicaIdOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ReplicaLoadInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaIdOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-804">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="c85ad-804">The partition ID.</span></span></para>
        </param>
        <param name="replicaIdOrInstanceId">
          <para><span data-ttu-id="c85ad-805">Der Replikat-ID (stateful Service) oder die Instanz-ID (statusfreien Dienst).</span><span class="sxs-lookup"><span data-stu-id="c85ad-805">The replica ID (stateful service) or instance ID (stateless service).</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-806">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-806">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-807">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-807">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-808">Erhalten Sie eine Liste der Metrik und ihre Arbeitslast auf einem Replikat aus.</span><span class="sxs-lookup"><span data-stu-id="c85ad-808">Get a list of metric and their load on a replica.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-809">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-809">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-810">Die zurückgegebene Aufgabe enthält die Informationen Laden des Replikats <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-810">The returned task contains the load information of the replica as <see cref="T:System.Fabric.Query.ReplicaLoadInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-811">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-811">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-812">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-812">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-813">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-813">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-814">Der Anwendungsname der Gruppe "Dienst".</span><span class="sxs-lookup"><span data-stu-id="c85ad-814">The application name of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-815">Abrufen von Dienst Gruppenmitgliedern einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-815">Get service group members of an application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-816">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-816">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-817">Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-817">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-818">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-818">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-819">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-819">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-820">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-820">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceGroupMemberList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-821">Der Anwendungsname der Gruppe "Dienst".</span><span class="sxs-lookup"><span data-stu-id="c85ad-821">The application name of the service group.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-822">Der Dienstname der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-822">The service name of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-823">Abrufen von Dienst Gruppenmitgliedern einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-823">Get service group members of an application.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-824">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-824">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-825">Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-825">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-826">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-826">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-827">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-827">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-828">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-828">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-829">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-829">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberList&gt; GetServiceGroupMemberListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;" Usage="queryClient.GetServiceGroupMemberListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-830">Der Anwendungsname der Gruppe "Dienst".</span><span class="sxs-lookup"><span data-stu-id="c85ad-830">The application name of the service group.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-831">Der Dienstname der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-831">The service name of the service group.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-832">Das Timeout des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c85ad-832">The timeout to the operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-833">Benachrichtigt, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-833">Notifies the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-834">Ruft die Details für alle Partitionen eines Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-834">Gets the details for all partitions of a service.</span></span> <span data-ttu-id="c85ad-835">Wenn die Partitionen auf einer Seite nicht ausreicht, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-835">If the partitions do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-836">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-836">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-837">Die zurückgegebene Aufgabe enthält die Liste der Gruppenmitglieder als Dienst <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-837">The returned task contains the list of service group members as <see cref="T:System.Fabric.Query.ServiceGroupMemberList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-838">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-838">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-839">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-839">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-840">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-840">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-841">Der Anwendungsname des Typs der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-841">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-842">Die anwendungstypversion der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-842">The application type version of the service group.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-843">Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-843">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-844">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-844">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-845">Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-845">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-846">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-846">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-847">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-847">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-848">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-848">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupMemberTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceGroupTypeNameFilter As String) As Task(Of ServiceGroupMemberTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-849">Der Anwendungsname des Typs der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-849">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-850">Die anwendungstypversion der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-850">The application type version of the service group.</span></span></para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para><span data-ttu-id="c85ad-851">Der Name des Diensttyps Gruppe abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-851">The name of the service group type to get.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-852">Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-852">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-853">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-853">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-854">Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-854">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-855">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-855">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-856">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-856">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-857">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-857">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-858">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-858">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupMemberTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceGroupMemberTypeList&gt; GetServiceGroupMemberTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceGroupTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceGroupMemberTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupMemberTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;" Usage="queryClient.GetServiceGroupMemberTypeListAsync (applicationTypeName, applicationTypeVersion, serviceGroupTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceGroupMemberTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceGroupTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-859">Der Anwendungsname des Typs der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-859">The application type name of the service group.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-860">Die anwendungstypversion der Dienstgruppe.</span><span class="sxs-lookup"><span data-stu-id="c85ad-860">The application type version of the service group.</span></span></para>
        </param>
        <param name="serviceGroupTypeNameFilter">
          <para><span data-ttu-id="c85ad-861">Der Name des Diensttyps Gruppe abgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-861">The name of the service group type to get.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-862">Das Timeout des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c85ad-862">The timeout to the operation.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-863">Benachrichtigt, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-863">Notifies the operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-864">Rufen Sie Service Gruppenmitglieder Fehlertypen Dienstgruppen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-864">Get service group members types of service group(s).</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-865">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-865">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-866">Die zurückgegebene Aufgabe enthält die Liste der Dienst Gruppe Elementtypen als <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-866">The returned task contains the list of service group member types as <see cref="T:System.Fabric.Query.ServiceGroupMemberTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-867">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-867">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-868">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-868">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-869">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-869">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync applicationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-870">Der Name der abzurufenden Dienste für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-870">The name of the application to get services for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-871">Ruft die Informationen zu allen Diensten, die an die Anwendung, die durch den Namen der Anwendung URI angegebenen gehören.</span><span class="sxs-lookup"><span data-stu-id="c85ad-871">Gets the information about all services belonging to the application specified by the application name URI.</span></span> <span data-ttu-id="c85ad-872">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-872">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-873">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-873">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-874">Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-874">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-875">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-875">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-876">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-876">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-877">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-877">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-878">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-878">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-879">Der Name der abzurufenden Dienste für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-879">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-880">Der Name der Dienste für ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-880">The name of the services to get details for.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-881">Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-881">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="c85ad-882">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-882">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-883">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-883">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-884">Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-884">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-885">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-885">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-886">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-886">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-887">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-887">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-888">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-888">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceListAsync (applicationName As Uri, serviceNameFilter As Uri, continuationToken As String) As Task(Of ServiceList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-889">Der Name der abzurufenden Dienste für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-889">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-890">Der Name der Dienste für ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-890">The name of the services to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-891">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-891">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-892">Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-892">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="c85ad-893">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-893">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-894">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-894">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-895">Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-895">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-896">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-896">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-897">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-897">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-898">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-898">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-899">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-899">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-900">Der Name der abzurufenden Dienste für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-900">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-901">Der Name der Dienste für ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-901">The name of the services to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-902">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-902">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-903">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-903">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-904">Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-904">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="c85ad-905">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-905">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-906">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-906">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-907">Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-907">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-908">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-908">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-909">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-909">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-910">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-910">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServiceListAsync (Uri applicationName, Uri serviceNameFilter, string continuationToken, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServiceListAsync(class System.Uri applicationName, class System.Uri serviceNameFilter, string continuationToken, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceListAsync(System.Uri,System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceListAsync : Uri * Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServiceListAsync (applicationName, serviceNameFilter, continuationToken, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceNameFilter" Type="System.Uri" />
        <Parameter Name="continuationToken" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="c85ad-911">Der Name der abzurufenden Dienste für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-911">The name of the application to get services for.</span></span></para>
        </param>
        <param name="serviceNameFilter">
          <para><span data-ttu-id="c85ad-912">Der Name der Dienste für ausführliche Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="c85ad-912">The name of the services to get details for.</span></span></para>
        </param>
        <param name="continuationToken">
          <para><span data-ttu-id="c85ad-913">Das Fortsetzungstoken aus einer vorherigen Abfrage abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-913">The continuation token obtained from a previous query.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-914">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-914">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-915">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-915">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="c85ad-916">Ruft die Details für alle Dienste einer Anwendung oder nur den angegebenen Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-916">Gets the details for all services of an application or just the specified service.</span></span> <span data-ttu-id="c85ad-917">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-917">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-918">Eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-918">A task that represents the asynchronous operation.</span></span></para>
          <para><span data-ttu-id="c85ad-919">Die zurückgegebene Aufgabe enthält die Liste der Dienste als <see cref="T:System.Fabric.Query.ServiceList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-919">The returned task contains the list of services as <see cref="T:System.Fabric.Query.ServiceList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-920">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-920">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-921">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-921">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-922">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-922">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceNameResult&gt; GetServiceNameAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceNameAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceNameAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;" Usage="queryClient.GetServiceNameAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceNameResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-923">Die Id der Partition, die den Dienstnamen für abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-923">The id of the partition to get the service name for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-924">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-924">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-925">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-925">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-926">Ruft den Dienstnamen für die angegebene Partition ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-926">Gets the service name for the specified partition.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-927">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-927">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-928">Die zurückgegebene Aufgabe enthält, der Dienstname als <see cref="T:System.Fabric.Query.ServiceNameResult" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-928">The returned task contains the service name as <see cref="T:System.Fabric.Query.ServiceNameResult" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-929">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-929">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-930">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-930">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-931">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-931">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync serviceQueryDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><span data-ttu-id="c85ad-932">Die <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> , der bestimmt, welche Dienste abgefragt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-932">The <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> that determines which services should be queried.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-933">Ruft die Details für alle Dienste einer Anwendung oder die angegebenen Dienste, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-933">Gets the details for all services of an application or just the specified services that match filters specified in query description (if any).</span></span> <span data-ttu-id="c85ad-934">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-934">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-935">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-935">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="c85ad-936">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ServiceList" /> , die die Liste der Dienste, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Query.ServiceList" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="c85ad-936">The value of TResult parameter is a <see cref="T:System.Fabric.Query.ServiceList" /> that represents the list of services that respect the filters in the <see cref="T:System.Fabric.Query.ServiceList" /> and fit the page.</span></span>
            <span data-ttu-id="c85ad-937">Wenn der bereitgestellte abfragebeschreibung keine passende Dienste verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-937">If the provided query description has no matching services, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-938">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-938">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-939">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-939">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-940">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-940">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServicePagedListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync (System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceList&gt; GetServicePagedListAsync(class System.Fabric.Description.ServiceQueryDescription serviceQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServicePagedListAsync(System.Fabric.Description.ServiceQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServicePagedListAsync : System.Fabric.Description.ServiceQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;" Usage="queryClient.GetServicePagedListAsync (serviceQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceQueryDescription" Type="System.Fabric.Description.ServiceQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceQueryDescription">
          <para><span data-ttu-id="c85ad-941">Die <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> , der bestimmt, welche Dienste abgefragt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-941">The <see cref="T:System.Fabric.Description.ServiceQueryDescription" /> that determines which services should be queried.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-942">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-942">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-943">Verteilen der Benachrichtigung, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="c85ad-943">Propagates notification that operation should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-944">Ruft die Details für alle Dienste einer Anwendung oder die angegebenen Dienste, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-944">Gets the details for all services of an application or just the specified services that match filters specified in query description (if any).</span></span> <span data-ttu-id="c85ad-945">Wenn die Dienste nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="c85ad-945">If the services do not fit in a page, one page of results is returned as well as a continuation token which can be used to get the next page.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-946">Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-946">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous query operation.</span></span> <span data-ttu-id="c85ad-947">Der Wert von TResult-Parameter ist ein <see cref="T:System.Fabric.Query.ServiceList" /> , die die Liste der Dienste, die die Filtern in respektieren darstellt der <see cref="T:System.Fabric.Query.ServiceList" /> und Anpassung an die Seite.</span><span class="sxs-lookup"><span data-stu-id="c85ad-947">The value of TResult parameter is a <see cref="T:System.Fabric.Query.ServiceList" /> that represents the list of services that respect the filters in the <see cref="T:System.Fabric.Query.ServiceList" /> and fit the page.</span></span>
            <span data-ttu-id="c85ad-948">Wenn der bereitgestellte abfragebeschreibung keine passende Dienste verfügt, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c85ad-948">If the provided query description has no matching services, it returns a list of 0 entries.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-949">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-949">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-950">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-950">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-951">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-951">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-952">Der Typname der Anwendung zum Abrufen von Diensttypen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-952">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-953">Die anwendungstypversion Diensttypen für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-953">The application type version to get service types for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-954">Ruft die Liste der Typen ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-954">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-955">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-955">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-956">Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-956">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-957">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-957">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-958">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-958">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-959">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-959">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceTypeListAsync (applicationTypeName As String, applicationTypeVersion As String, serviceTypeNameFilter As String) As Task(Of ServiceTypeList)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-960">Der Typname der Anwendung zum Abrufen von Diensttypen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-960">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-961">Die anwendungstypversion Diensttypen für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-961">The application type version to get service types for.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="c85ad-962">Der Name des abzurufenden Details für den Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="c85ad-962">The name of the service type to get details for.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-963">Ruft die Liste der Typen ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-963">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-964">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-964">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-965">Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-965">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-966">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-966">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-967">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-967">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-968">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-968">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-969">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-969">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceTypeListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync (string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.ServiceTypeList&gt; GetServiceTypeListAsync(string applicationTypeName, string applicationTypeVersion, string serviceTypeNameFilter, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetServiceTypeListAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceTypeListAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;" Usage="queryClient.GetServiceTypeListAsync (applicationTypeName, applicationTypeVersion, serviceTypeNameFilter, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.ServiceTypeList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceTypeNameFilter" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para><span data-ttu-id="c85ad-970">Der Typname der Anwendung zum Abrufen von Diensttypen für.</span><span class="sxs-lookup"><span data-stu-id="c85ad-970">The type name of the application to get service types for.</span></span></para>
        </param>
        <param name="applicationTypeVersion">
          <para><span data-ttu-id="c85ad-971">Die anwendungstypversion Diensttypen für abgerufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-971">The application type version to get service types for.</span></span></para>
        </param>
        <param name="serviceTypeNameFilter">
          <para><span data-ttu-id="c85ad-972">Der Name des abzurufenden Details für den Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="c85ad-972">The name of the service type to get details for.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-973">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-973">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-974">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-974">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-975">Ruft die Liste der Typen ab.</span><span class="sxs-lookup"><span data-stu-id="c85ad-975">Gets the list of service types.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-976">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-976">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-977">Die zurückgegebene Aufgabe enthält die Liste von Diensttypen als <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-977">The returned task contains the list of service types as <see cref="T:System.Fabric.Query.ServiceTypeList" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-978">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-978">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-979">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-979">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-980">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-980">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUnplacedReplicaInformationAsync (serviceName As String, partitionId As Guid, onlyQueryPrimaries As Boolean) As Task(Of UnplacedReplicaInformation)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-981">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-981">The name of the service.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-982">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="c85ad-982">The partition ID.</span></span></para>
        </param>
        <param name="onlyQueryPrimaries">
          <para><span data-ttu-id="c85ad-983">Zurückkehren Sie nur die nicht positionierte Replikat Diagnose nur die versuchte primären replikatplatzierungen, um die Ausgabe zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="c85ad-983">Return only the unplaced replica diagnostics for only the attempted primary replica placements in order to limit output.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-984">Diagnoseinformationen über Dienste mit nicht positionierte Replikate abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-984">Get diagnostics information about services with unplaced replicas.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-985">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-985">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-986">Die zurückgegebene Aufgabe enthält die Informationen eines nicht positionierte Replikats als <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-986">The returned task contains the information of an unplaced replica as <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-987">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-987">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="c85ad-988">Dieser Vorgang ist ein Timeout von 60 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="c85ad-988">This operation has a timeout of 60 seconds.</span></span></para>
          <para>
                <span data-ttu-id="c85ad-989">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-989">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-990">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-990">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUnplacedReplicaInformationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync (string serviceName, Guid partitionId, bool onlyQueryPrimaries, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Query.UnplacedReplicaInformation&gt; GetUnplacedReplicaInformationAsync(string serviceName, valuetype System.Guid partitionId, bool onlyQueryPrimaries, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.QueryClient.GetUnplacedReplicaInformationAsync(System.String,System.Guid,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUnplacedReplicaInformationAsync : string * Guid * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;" Usage="queryClient.GetUnplacedReplicaInformationAsync (serviceName, partitionId, onlyQueryPrimaries, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Query.UnplacedReplicaInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="onlyQueryPrimaries" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="c85ad-991">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c85ad-991">The name of the service.</span></span></para>
        </param>
        <param name="partitionId">
          <para><span data-ttu-id="c85ad-992">Die Partitions-ID.</span><span class="sxs-lookup"><span data-stu-id="c85ad-992">The partition ID.</span></span></para>
        </param>
        <param name="onlyQueryPrimaries">
          <para><span data-ttu-id="c85ad-993">Zurückkehren Sie nur die nicht positionierte Replikat Diagnose nur die versuchte primären replikatplatzierungen, um die Ausgabe zu beschränken.</span><span class="sxs-lookup"><span data-stu-id="c85ad-993">Return only the unplaced replica diagnostics for only the attempted primary replica placements in order to limit output.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="c85ad-994">Gibt die Dauer dieses Vorgangs muss, bevor ein Timeout eintritt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-994">Specifies the duration this operation has to complete before timing out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="c85ad-995">Gibt eine Benachrichtigung darüber weiter, dass Vorgänge abgebrochen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-995">Propagates notification that operations should be canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="c85ad-996">Diagnoseinformationen über Dienste mit nicht positionierte Replikate abrufen.</span><span class="sxs-lookup"><span data-stu-id="c85ad-996">Get diagnostics information about services with unplaced replicas.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="c85ad-997">Eine Aufgabe, die den asynchronen Abfragevorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="c85ad-997">A task that represents the asynchronous query operation.</span></span></para>
          <para><span data-ttu-id="c85ad-998">Die zurückgegebene Aufgabe enthält die Informationen eines nicht positionierte Replikats als <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span><span class="sxs-lookup"><span data-stu-id="c85ad-998">The returned task contains the information of an unplaced replica as <see cref="T:System.Fabric.Query.UnplacedReplicaInformation" />.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="c85ad-999">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-999">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="c85ad-1000">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="c85ad-1000">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="c85ad-1001">Siehe auch <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="c85ad-1001">See also <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-errors-and-exceptions" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>