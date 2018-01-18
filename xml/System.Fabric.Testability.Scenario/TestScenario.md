<Type Name="TestScenario" FullName="System.Fabric.Testability.Scenario.TestScenario">
  <TypeSignature Language="C#" Value="public abstract class TestScenario : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TestScenario extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Testability.Scenario.TestScenario" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TestScenario&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TestScenario = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="49f90-101">Die Basisklasse für TestScenarios, die alle allgemeinen Methoden und Funktionen definiert werden.</span><span class="sxs-lookup"><span data-stu-id="49f90-101">Base class for TestScenarios which defines all the common methods and functionality.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal TestScenario (System.Fabric.FabricClient fabricClient, System.Fabric.Testability.Scenario.TestScenarioParameters testScenarioParameters);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClient fabricClient, class System.Fabric.Testability.Scenario.TestScenarioParameters testScenarioParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.#ctor(System.Fabric.FabricClient,System.Fabric.Testability.Scenario.TestScenarioParameters)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Testability.Scenario.TestScenario : System.Fabric.FabricClient * System.Fabric.Testability.Scenario.TestScenarioParameters -&gt; System.Fabric.Testability.Scenario.TestScenario" Usage="new System.Fabric.Testability.Scenario.TestScenario (fabricClient, testScenarioParameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fabricClient" Type="System.Fabric.FabricClient" />
        <Parameter Name="testScenarioParameters" Type="System.Fabric.Testability.Scenario.TestScenarioParameters" />
      </Parameters>
      <Docs>
        <param name="fabricClient"><span data-ttu-id="49f90-102">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-102">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <param name="testScenarioParameters"><span data-ttu-id="49f90-103">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-103">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-104">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-104">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="testScenario.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49f90-105">Diese Methode gibt die TestScenario frei.</span><span class="sxs-lookup"><span data-stu-id="49f90-105">This method will dispose the TestScenario.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.ExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="member this.ExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testScenario.ExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.Testability.Scenario.TestScenario/&lt;ExecuteAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="49f90-106">das Abbruchtoken, das für den asynchronen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="49f90-106">the Cancellation token for the async operation.</span></span></param>
        <summary>
            <span data-ttu-id="49f90-107">Diese Methode führt den Test mit dem angegebenen Parameter, die an den Konstruktor übergebene festgelegt.</span><span class="sxs-lookup"><span data-stu-id="49f90-107">This method executes the test with the specified parameter set passed into the constructor.</span></span>
            </summary>
        <returns><span data-ttu-id="49f90-108">Gibt eine Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="49f90-108">Returns a Task which represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricValidationException"><span data-ttu-id="49f90-109">Wenn Sie jeden beliebigen Dienst nicht innerhalb des angegebenen Timeouts stabilisiert werden.</span><span class="sxs-lookup"><span data-stu-id="49f90-109">If any service does not stabilize within the specified timeout.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="FabricClient">
      <MemberSignature Language="C#" Value="protected System.Fabric.FabricClient FabricClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient FabricClient" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.TestScenario.FabricClient" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property FabricClient As FabricClient" />
      <MemberSignature Language="F#" Value="member this.FabricClient : System.Fabric.FabricClient" Usage="System.Fabric.Testability.Scenario.TestScenario.FabricClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49f90-110">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-110">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <value>
            <span data-ttu-id="49f90-111">Gibt <see cref="T:System.Fabric.FabricClient" />zurück.</span><span class="sxs-lookup"><span data-stu-id="49f90-111">Returns <see cref="T:System.Fabric.FabricClient" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetElapsedTime">
      <MemberSignature Language="C#" Value="protected TimeSpan GetElapsedTime ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance valuetype System.TimeSpan GetElapsedTime() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.GetElapsedTime" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetElapsedTime () As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.GetElapsedTime : unit -&gt; TimeSpan" Usage="testScenario.GetElapsedTime " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49f90-112">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-112">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns><span data-ttu-id="49f90-113">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-113">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandleTaskComplete">
      <MemberSignature Language="C#" Value="protected void HandleTaskComplete (System.Threading.Tasks.Task t, string actionId, string actionName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void HandleTaskComplete(class System.Threading.Tasks.Task t, string actionId, string actionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.HandleTaskComplete(System.Threading.Tasks.Task,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub HandleTaskComplete (t As Task, actionId As String, actionName As String)" />
      <MemberSignature Language="F#" Value="member this.HandleTaskComplete : System.Threading.Tasks.Task * string * string -&gt; unit" Usage="testScenario.HandleTaskComplete (t, actionId, actionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="t" Type="System.Threading.Tasks.Task" />
        <Parameter Name="actionId" Type="System.String" />
        <Parameter Name="actionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="t"><span data-ttu-id="49f90-114">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-114">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <param name="actionId"><span data-ttu-id="49f90-115">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-115">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <param name="actionName"><span data-ttu-id="49f90-116">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-116">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-117">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-117">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispose">
      <MemberSignature Language="C#" Value="protected abstract void OnDispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.OnDispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnDispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member OnDispose : bool -&gt; unit" Usage="testScenario.OnDispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing"><span data-ttu-id="49f90-118">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-118">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-119">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-119">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnExecuteAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task OnExecuteAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnExecuteAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.OnExecuteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnExecuteAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="abstract member OnExecuteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testScenario.OnExecuteAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="49f90-120">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-120">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-121">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-121">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns><span data-ttu-id="49f90-122">Eine Aufgabe, die die Ausführung der TestScenario darstellt.</span><span class="sxs-lookup"><span data-stu-id="49f90-122">A task representing the execution of the TestScenario.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProgressChanged">
      <MemberSignature Language="C#" Value="public System.ComponentModel.ProgressChangedEventHandler ProgressChanged;" />
      <MemberSignature Language="ILAsm" Value=".field public class System.ComponentModel.ProgressChangedEventHandler ProgressChanged" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.Testability.Scenario.TestScenario.ProgressChanged" />
      <MemberSignature Language="VB.NET" Value="Public ProgressChanged As ProgressChangedEventHandler " />
      <MemberSignature Language="F#" Value="val mutable ProgressChanged : System.ComponentModel.ProgressChangedEventHandler" Usage="System.Fabric.Testability.Scenario.TestScenario.ProgressChanged" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.ComponentModel.ProgressChangedEventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49f90-123">Ereignishandler, die den aktuellen Status des Tests verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="49f90-123">Event handler which exposes the current progress of the test.</span></span> <span data-ttu-id="49f90-124">Wenn sie bietet verarbeitet ausgeführt Sie die ProgressChangedEventArgs die gewährt, eine gesamt % des Tests, die bereits abgeschlossen wurde, und der letzte Vorgang (String), die die für die Protokollierung nützlich sein können.</span><span class="sxs-lookup"><span data-stu-id="49f90-124">When handled it gives you the ProgressChangedEventArgs which gives out a total % of the test which has already completed and the last operation (string) that was performed which can be useful for logging.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportProgress">
      <MemberSignature Language="C#" Value="protected void ReportProgress (string progressReport);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ReportProgress(string progressReport) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.ReportProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ReportProgress (progressReport As String)" />
      <MemberSignature Language="F#" Value="member this.ReportProgress : string -&gt; unit" Usage="testScenario.ReportProgress progressReport" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="progressReport" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="progressReport"><span data-ttu-id="49f90-125">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-125">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-126">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-126">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReportProgress">
      <MemberSignature Language="C#" Value="protected void ReportProgress (string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ReportProgress(string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.ReportProgress(System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ReportProgress (format As String, ParamArray args As Object())" />
      <MemberSignature Language="F#" Value="member this.ReportProgress : string * obj[] -&gt; unit" Usage="testScenario.ReportProgress (format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="format"><span data-ttu-id="49f90-127">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-127">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <param name="args"><span data-ttu-id="49f90-128">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-128">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-129">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-129">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScenarioParameters">
      <MemberSignature Language="C#" Value="protected System.Fabric.Testability.Scenario.TestScenarioParameters ScenarioParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Testability.Scenario.TestScenarioParameters ScenarioParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Testability.Scenario.TestScenario.ScenarioParameters" />
      <MemberSignature Language="VB.NET" Value="Protected ReadOnly Property ScenarioParameters As TestScenarioParameters" />
      <MemberSignature Language="F#" Value="member this.ScenarioParameters : System.Fabric.Testability.Scenario.TestScenarioParameters" Usage="System.Fabric.Testability.Scenario.TestScenario.ScenarioParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Testability.Scenario.TestScenarioParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49f90-130">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-130">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <value>
            <span data-ttu-id="49f90-131">Gibt <see cref="T:System.Fabric.Testability.Scenario.TestScenarioParameters" />zurück.</span><span class="sxs-lookup"><span data-stu-id="49f90-131">Returns <see cref="T:System.Fabric.Testability.Scenario.TestScenarioParameters" />.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateScenarioAtExitAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task ValidateScenarioAtExitAsync (System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task ValidateScenarioAtExitAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Testability.Scenario.TestScenario.ValidateScenarioAtExitAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function ValidateScenarioAtExitAsync (token As CancellationToken) As Task" />
      <MemberSignature Language="F#" Value="abstract member ValidateScenarioAtExitAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="testScenario.ValidateScenarioAtExitAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="49f90-132">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-132">This API supports the Service Fabric platform and is not meant to be called from your code</span></span></param>
        <summary>
            <span data-ttu-id="49f90-133">Diese API unterstützt die Service Fabric-Plattform und ist nicht vorgesehen, aus dem Code aufgerufen werden</span><span class="sxs-lookup"><span data-stu-id="49f90-133">This API supports the Service Fabric platform and is not meant to be called from your code</span></span>
            </summary>
        <returns><span data-ttu-id="49f90-134">Eine Aufgabe, die den Überprüfungsvorgang - Implementierung von abgeleiteten TestScenario - darstellt, führen Sie nach Abschluss der OnExecuteAsync muss.</span><span class="sxs-lookup"><span data-stu-id="49f90-134">A task representing the validation operation - implemented by the derived TestScenario - that needs to run when OnExecuteAsync has completed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>