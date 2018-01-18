<Type Name="FunctionsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class FunctionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit FunctionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module FunctionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type FunctionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4d125-101">Erweiterungsmethoden für FunctionsOperations.</span><span class="sxs-lookup"><span data-stu-id="4d125-101">Extension methods for FunctionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-105">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-105">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-106">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-106">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-107">Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4d125-107">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="4d125-108">Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-108">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-109">Testet, ob die Informationen für eine Funktion ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-109">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="4d125-110">Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-110">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;BeginTestAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-111">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-112">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-112">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-113">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-113">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-114">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-114">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-115">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-115">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-116">Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4d125-116">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="4d125-117">Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-117">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-119">Testet, ob die Informationen für eine Funktion ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-119">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="4d125-120">Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-120">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplace (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-121">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-122">Die Definition der Funktion, die zum Erstellen Sie eine neue Funktion, oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-122">The definition of the function that will be used to create a new function or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-123">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-123">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-124">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-124">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-125">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-125">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-126">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-126">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="4d125-127">Das ETag der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-127">The ETag of the function.</span></span> <span data-ttu-id="4d125-128">Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="4d125-128">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="4d125-129">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="4d125-129">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="4d125-130">Legen Sie auf "\*" um eine neue Funktion erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Funktion zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="4d125-130">Set to '\*' to allow a new function to be created, but to prevent updating an existing function.</span></span> <span data-ttu-id="4d125-131">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-131">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-132">Erstellt eine Funktion oder eine bereits vorhandene Funktion unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="4d125-132">Creates a function or replaces an already existing function under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.CreateOrReplaceAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-133">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-134">Die Definition der Funktion, die zum Erstellen Sie eine neue Funktion, oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-134">The definition of the function that will be used to create a new function or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-135">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-135">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-136">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-136">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-137">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-137">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-138">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-138">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="4d125-139">Das ETag der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-139">The ETag of the function.</span></span> <span data-ttu-id="4d125-140">Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="4d125-140">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="4d125-141">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="4d125-141">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="4d125-142">Legen Sie auf "\*" um eine neue Funktion erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Funktion zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="4d125-142">Set to '\*' to allow a new function to be created, but to prevent updating an existing function.</span></span> <span data-ttu-id="4d125-143">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-143">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-145">Erstellt eine Funktion oder eine bereits vorhandene Funktion unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="4d125-145">Creates a function or replaces an already existing function under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Delete (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-147">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-147">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-148">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-149">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-149">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-150">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-150">The name of the function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-151">Löscht eine Funktion aus den streamingauftrag an.</span><span class="sxs-lookup"><span data-stu-id="4d125-151">Deletes a function from the streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-153">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-153">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-154">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-154">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-155">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-155">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-156">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-156">The name of the function.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-158">Löscht eine Funktion aus den streamingauftrag an.</span><span class="sxs-lookup"><span data-stu-id="4d125-158">Deletes a function from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Get (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Get(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, functionName As String) As Function" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Get (operations, resourceGroupName, jobName, functionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-160">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-160">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-161">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-161">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-162">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-162">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-163">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-163">The name of the function.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-164">Ruft Details über die angegebene Funktion ab.</span><span class="sxs-lookup"><span data-stu-id="4d125-164">Gets details about the specified function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, functionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-166">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-167">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-168">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-168">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-169">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-169">The name of the function.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-171">Ruft Details über die angegebene Funktion ab.</span><span class="sxs-lookup"><span data-stu-id="4d125-171">Gets details about the specified function.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IFunctionsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-173">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-173">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-174">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-174">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-175">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-175">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="4d125-176">Der $select OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="4d125-176">The $select OData query parameter.</span></span> <span data-ttu-id="4d125-177">Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.</span><span class="sxs-lookup"><span data-stu-id="4d125-177">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-178">Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-178">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-180">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-180">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-181">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-181">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-182">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-182">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="4d125-183">Der $select OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="4d125-183">The $select OData query parameter.</span></span> <span data-ttu-id="4d125-184">Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.</span><span class="sxs-lookup"><span data-stu-id="4d125-184">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-186">Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-186">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IFunctionsOperations, nextPageLink As String) As IPage(Of Function)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-187">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4d125-188">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4d125-188">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-189">Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-189">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-190">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4d125-191">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4d125-191">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-193">Zeigt eine Liste aller Funktionen unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-193">Lists all of the functions under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function RetrieveDefaultDefinition(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinition : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinition (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-194">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-195">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-195">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-196">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-196">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-197">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-197">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-198">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-198">The name of the function.</span></span>
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            <span data-ttu-id="4d125-199">Der Parameter verwendet, um den Typ der Funktion das Default-Definition für die abzurufenden anzugeben.</span><span class="sxs-lookup"><span data-stu-id="4d125-199">Parameters used to specify the type of function to retrieve the default definition for.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-200">Ruft die Default-Definition einer Funktion, die basierend auf den angegebenen Parametern ab.</span><span class="sxs-lookup"><span data-stu-id="4d125-200">Retrieves the default definition of a function based on the parameters specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetrieveDefaultDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; RetrieveDefaultDefinitionAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters functionRetrieveDefaultDefinitionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RetrieveDefaultDefinitionAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.RetrieveDefaultDefinitionAsync (operations, resourceGroupName, jobName, functionName, functionRetrieveDefaultDefinitionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;RetrieveDefaultDefinitionAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="functionRetrieveDefaultDefinitionParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.FunctionRetrieveDefaultDefinitionParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-202">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-202">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-203">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-203">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-204">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-204">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-205">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-205">The name of the function.</span></span>
            </param>
        <param name="functionRetrieveDefaultDefinitionParameters">
            <span data-ttu-id="4d125-206">Der Parameter verwendet, um den Typ der Funktion das Default-Definition für die abzurufenden anzugeben.</span><span class="sxs-lookup"><span data-stu-id="4d125-206">Parameters used to specify the type of function to retrieve the default definition for.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-208">Ruft die Default-Definition einer Funktion, die basierend auf den angegebenen Parametern ab.</span><span class="sxs-lookup"><span data-stu-id="4d125-208">Retrieves the default definition of a function based on the parameters specified.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Test (operations, resourceGroupName, jobName, functionName, function)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-209">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-210">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-210">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-211">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-211">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-212">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-212">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-213">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-213">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-214">Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4d125-214">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="4d125-215">Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-215">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-216">Testet, ob die Informationen für eine Funktion ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-216">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="4d125-217">Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-217">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, Microsoft.Azure.Management.StreamAnalytics.Models.Function function = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, string resourceGroupName, string jobName, string functionName, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Function * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, functionName, function, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-219">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-219">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-220">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-220">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-221">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-221">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-222">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-222">The name of the function.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-223">Wenn die angegebene Funktion nicht bereits vorhanden ist, darf dieser Parameter die vollständigen Definition der getestet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4d125-223">If the function specified does not already exist, this parameter must contain the full function definition intended to be tested.</span></span> <span data-ttu-id="4d125-224">Wenn die Funktion, die bereits vorhanden ist, dieser Parameter kann null, wenn die vorhandene Funktion ist oder wenn der angegebene testen links, die angegebenen Eigenschaften werden die entsprechenden Eigenschaften in der vorhandenen-Funktion (genau wie ein PATCH-Vorgang) überschrieben und die resultierende Funktion wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-224">If the function specified already exists, this parameter can be left null to test the existing function as is or if specified, the properties specified will overwrite the corresponding properties in the existing function (exactly like a PATCH operation) and the resulting function will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-226">Testet, ob die Informationen für eine Funktion ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-226">Tests if the information provided for a function is valid.</span></span> <span data-ttu-id="4d125-227">Diese liegen im Bereich von Testen der Verbindung mit dem zugrunde liegenden Webdienst hinter der Funktion oder sicherstellen, dass die bereitgestellte Funktionscode syntaktisch richtig ist.</span><span class="sxs-lookup"><span data-stu-id="4d125-227">This can range from testing the connection to the underlying web service behind the function or making sure the function code provided is syntactically correct.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Function Update (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Function Update(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Function" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.Update (operations, function, resourceGroupName, jobName, functionName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Function</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-228">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-229">Ein Funktionsobjekt.</span><span class="sxs-lookup"><span data-stu-id="4d125-229">A function object.</span></span> <span data-ttu-id="4d125-230">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen-Funktion (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="4d125-230">The properties specified here will overwrite the corresponding properties in the existing function (ie. Those properties will be updated).</span></span> <span data-ttu-id="4d125-231">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in die vorhandene Funktion gleich bleiben und nicht als Ergebnis dieser PATCH-Vorgang geändert wird.</span><span class="sxs-lookup"><span data-stu-id="4d125-231">Any properties that are set to null here will mean that the corresponding property in the existing function will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-232">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-232">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-233">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-233">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-234">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-234">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-235">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-235">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="4d125-236">Das ETag der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-236">The ETag of the function.</span></span> <span data-ttu-id="4d125-237">Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="4d125-237">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="4d125-238">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="4d125-238">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-239">Aktualisiert eine vorhandene Funktion unter einer vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="4d125-239">Updates an existing function under an existing streaming job.</span></span> <span data-ttu-id="4d125-240">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="4d125-240">This can be used to partially update (ie.</span></span> <span data-ttu-id="4d125-241">Aktualisieren Sie eine oder zwei Eigenschaften) einer Funktion ohne den Rest der Auftrag oder Funktionsdefinition.</span><span class="sxs-lookup"><span data-stu-id="4d125-241">update one or two properties) a function without affecting the rest the job or function definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Function function, string resourceGroupName, string jobName, string functionName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Function,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Function * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions.UpdateAsync (operations, function, resourceGroupName, jobName, functionName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.FunctionsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IFunctionsOperations" RefType="this" />
        <Parameter Name="function" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Function" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="functionName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4d125-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4d125-242">The operations group for this extension method.</span></span>
            </param>
        <param name="function">
            <span data-ttu-id="4d125-243">Ein Funktionsobjekt.</span><span class="sxs-lookup"><span data-stu-id="4d125-243">A function object.</span></span> <span data-ttu-id="4d125-244">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen-Funktion (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="4d125-244">The properties specified here will overwrite the corresponding properties in the existing function (ie. Those properties will be updated).</span></span> <span data-ttu-id="4d125-245">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in die vorhandene Funktion gleich bleiben und nicht als Ergebnis dieser PATCH-Vorgang geändert wird.</span><span class="sxs-lookup"><span data-stu-id="4d125-245">Any properties that are set to null here will mean that the corresponding property in the existing function will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4d125-246">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="4d125-246">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="4d125-247">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="4d125-247">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="4d125-248">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="4d125-248">The name of the streaming job.</span></span>
            </param>
        <param name="functionName">
            <span data-ttu-id="4d125-249">Der Name der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-249">The name of the function.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="4d125-250">Das ETag der Funktion.</span><span class="sxs-lookup"><span data-stu-id="4d125-250">The ETag of the function.</span></span> <span data-ttu-id="4d125-251">Lassen Sie diesen Wert, um die aktuelle Funktion immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="4d125-251">Omit this value to always overwrite the current function.</span></span> <span data-ttu-id="4d125-252">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="4d125-252">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4d125-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4d125-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4d125-254">Aktualisiert eine vorhandene Funktion unter einer vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="4d125-254">Updates an existing function under an existing streaming job.</span></span> <span data-ttu-id="4d125-255">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="4d125-255">This can be used to partially update (ie.</span></span> <span data-ttu-id="4d125-256">Aktualisieren Sie eine oder zwei Eigenschaften) einer Funktion ohne den Rest der Auftrag oder Funktionsdefinition.</span><span class="sxs-lookup"><span data-stu-id="4d125-256">update one or two properties) a function without affecting the rest the job or function definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>