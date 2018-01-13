<Type Name="InputsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InputsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InputsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InputsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InputsOperationsExtensions = class" />
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
            <span data-ttu-id="fd2f5-101">Erweiterungsmethoden für InputsOperations.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-101">Extension methods for InputsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginTest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus BeginTest(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member BeginTest : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTest (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-105">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-105">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-106">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-106">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-107">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-107">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="fd2f5-108">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-108">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-109">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-109">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; BeginTestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.BeginTestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;BeginTestAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-111">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-111">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-112">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-113">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-113">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-114">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-114">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-115">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-115">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="fd2f5-116">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-116">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-118">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-118">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplace (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-119">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-120">Die Definition der Eingabe, die eine neue Eingabe erstellen oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-120">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-121">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-121">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-122">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-122">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-123">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-123">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-124">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-124">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fd2f5-125">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-125">The ETag of the input.</span></span> <span data-ttu-id="fd2f5-126">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-126">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="fd2f5-127">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-127">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="fd2f5-128">Legen Sie auf "\*" um eine neue Eingabe erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Eingabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-128">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="fd2f5-129">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-129">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-130">Erstellt eine Eingabe, oder eine bereits vorhandene Eingabe unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-130">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.CreateOrReplaceAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-131">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-132">Die Definition der Eingabe, die eine neue Eingabe erstellen oder Ersetzen von vorhandenen Knoten unter der streamingauftrag verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-132">The definition of the input that will be used to create a new input or replace the existing one under the streaming job.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-133">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-133">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-134">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-134">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-135">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-135">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-136">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-136">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fd2f5-137">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-137">The ETag of the input.</span></span> <span data-ttu-id="fd2f5-138">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-138">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="fd2f5-139">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-139">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="fd2f5-140">Legen Sie auf "\*" um eine neue Eingabe erstellt werden, sondern um zu verhindern, aktualisieren eine vorhandene Eingabe zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-140">Set to '\*' to allow a new input to be created, but to prevent updating an existing input.</span></span> <span data-ttu-id="fd2f5-141">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-141">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-143">Erstellt eine Eingabe, oder eine bereits vorhandene Eingabe unter einem vorhandenen streaming Auftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-143">Creates an input or replaces an already existing input under an existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Delete (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-145">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-145">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-146">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-147">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-147">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-148">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-148">The name of the input.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-149">Löscht eine Eingabe aus der streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-149">Deletes an input from the streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-151">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-151">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-152">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-152">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-153">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-153">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-154">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-154">The name of the input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-156">Löscht eine Eingabe aus der streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-156">Deletes an input from the streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Get (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Get(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInputsOperations, resourceGroupName As String, jobName As String, inputName As String) As Input" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Get (operations, resourceGroupName, jobName, inputName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-158">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-159">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-160">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-160">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-161">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-161">The name of the input.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-162">Ruft Details über die angegebene Eingabe ab.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-162">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, inputName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-164">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-164">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-165">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-165">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-166">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-166">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-167">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-167">The name of the input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-169">Ruft Details über die angegebene Eingabe ab.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-169">Gets details about the specified input.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJob">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJob(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJob (operations As IInputsOperations, resourceGroupName As String, jobName As String, Optional select As String = null) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJob : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJob (operations, resourceGroupName, jobName, select)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-171">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-172">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-173">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-173">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="fd2f5-174">Der $select OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-174">The $select OData query parameter.</span></span> <span data-ttu-id="fd2f5-175">Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-175">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-176">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-176">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string select, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobAsync (operations, resourceGroupName, jobName, select, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-178">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-178">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-179">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-179">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-180">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-180">The name of the streaming job.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="fd2f5-181">Der $select OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-181">The $select OData query parameter.</span></span> <span data-ttu-id="fd2f5-182">Dies ist eine durch Trennzeichen getrennte Liste der strukturellen Eigenschaften in die Antwort eingeschlossen werden sollen oder "*" alle Eigenschaften eingeschlossen. Standardmäßig werden alle Eigenschaften außer Diagnose zurückgegeben. Derzeit sind nur Werte "*" als gültiger Wert.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-182">This is a comma-separated list of structural properties to include in the response, or “*” to include all properties. By default, all properties are returned except diagnostics. Currently only accepts '*' as a valid value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-184">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-184">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; ListByStreamingJobNext(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByStreamingJobNext (operations As IInputsOperations, nextPageLink As String) As IPage(Of Input)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNext : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-185">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fd2f5-186">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-187">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-187">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByStreamingJobNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt; ListByStreamingJobNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByStreamingJobNextAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.ListByStreamingJobNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;ListByStreamingJobNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fd2f5-189">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-191">Zeigt eine Liste aller Eingaben unter dem angegebenen streaming-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-191">Lists all of the inputs under the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Test">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus Test(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input)" />
      <MemberSignature Language="F#" Value="static member Test : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Test (operations, resourceGroupName, jobName, inputName, input)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-193">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-194">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-195">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-195">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-196">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-196">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-197">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-197">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="fd2f5-198">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-198">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-199">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-199">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, Microsoft.Azure.Management.StreamAnalytics.Models.Input input = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt; TestAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, string resourceGroupName, string jobName, string inputName, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TestAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * string * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.Input * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.TestAsync (operations, resourceGroupName, jobName, inputName, input, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;TestAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.ResourceTestStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-201">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-201">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-202">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-202">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-203">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-203">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-204">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-204">The name of the input.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-205">Wenn die angegebene Eingabe nicht bereits vorhanden ist, muss dieser Parameter die vollständige eingabedefinition getestet werden soll enthalten.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-205">If the input specified does not already exist, this parameter must contain the full input definition intended to be tested.</span></span> <span data-ttu-id="fd2f5-206">Wenn die Eingabe, die bereits vorhanden ist, dieser Parameter kann null So testen Sie die vorhandene Eingabe unverändert gelassen werden oder wenn angegeben, überschreibt die angegebenen Eigenschaften der entsprechenden Eigenschaften in die vorhandene Eingabe (genau wie ein PATCH-Vorgang) und das resultierende Eingabe wird getestet werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-206">If the input specified already exists, this parameter can be left null to test the existing input as is or if specified, the properties specified will overwrite the corresponding properties in the existing input (exactly like a PATCH operation) and the resulting input will be tested.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-207">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-207">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-208">Testet, ob eine Eingabe-Datenquelle erreichbar und von Azure Stream Analytics-Dienst verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-208">Tests whether an input’s datasource is reachable and usable by the Azure Stream Analytics service.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.Input Update (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.Input Update(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.Input" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.Update (operations, input, resourceGroupName, jobName, inputName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Input</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-209">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-210">Ein Input-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-210">An Input object.</span></span> <span data-ttu-id="fd2f5-211">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Eingabe (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="fd2f5-211">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="fd2f5-212">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-212">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-213">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-213">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-214">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-214">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-215">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-215">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-216">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-216">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fd2f5-217">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-217">The ETag of the input.</span></span> <span data-ttu-id="fd2f5-218">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-218">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="fd2f5-219">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-219">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-220">Aktualisiert eine vorhandene Eingabe unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-220">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="fd2f5-221">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-221">This can be used to partially update (ie.</span></span> <span data-ttu-id="fd2f5-222">Aktualisieren Sie eine oder zwei Eigenschaften) Eingabe ohne den Rest der Auftrag oder die Eingabe-Definition.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-222">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IInputsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.Input input, string resourceGroupName, string jobName, string inputName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IInputsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.Input,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IInputsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.Input * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions.UpdateAsync (operations, input, resourceGroupName, jobName, inputName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.InputsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IInputsOperations" RefType="this" />
        <Parameter Name="input" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Input" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="inputName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fd2f5-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-223">The operations group for this extension method.</span></span>
            </param>
        <param name="input">
            <span data-ttu-id="fd2f5-224">Ein Input-Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-224">An Input object.</span></span> <span data-ttu-id="fd2f5-225">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen Eingabe (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="fd2f5-225">The properties specified here will overwrite the corresponding properties in the existing input (ie. Those properties will be updated).</span></span> <span data-ttu-id="fd2f5-226">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-226">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fd2f5-227">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="fd2f5-228">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="fd2f5-229">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-229">The name of the streaming job.</span></span>
            </param>
        <param name="inputName">
            <span data-ttu-id="fd2f5-230">Der Name der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-230">The name of the input.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="fd2f5-231">Das ETag der Eingabe.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-231">The ETag of the input.</span></span> <span data-ttu-id="fd2f5-232">Lassen Sie diesen Wert, um die aktuelle Eingabe immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-232">Omit this value to always overwrite the current input.</span></span> <span data-ttu-id="fd2f5-233">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-233">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd2f5-234">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd2f5-235">Aktualisiert eine vorhandene Eingabe unter einem vorhandenen streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-235">Updates an existing input under an existing streaming job.</span></span> <span data-ttu-id="fd2f5-236">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-236">This can be used to partially update (ie.</span></span> <span data-ttu-id="fd2f5-237">Aktualisieren Sie eine oder zwei Eigenschaften) Eingabe ohne den Rest der Auftrag oder die Eingabe-Definition.</span><span class="sxs-lookup"><span data-stu-id="fd2f5-237">update one or two properties) an input without affecting the rest the job or input definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>