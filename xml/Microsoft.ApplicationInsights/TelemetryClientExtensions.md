<Type Name="TelemetryClientExtensions" FullName="Microsoft.ApplicationInsights.TelemetryClientExtensions">
  <TypeSignature Language="C#" Value="public static class TelemetryClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TelemetryClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.TelemetryClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TelemetryClientExtensions" />
  <TypeSignature Language="F#" Value="type TelemetryClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="da1ae-101">Der Erweiterungsklasse an Telemetrie-Client, der Vorgang Objekt mit den entsprechenden Feldern initialisiert erstellt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-101">Extension class to telemetry client that creates operation object with the respective fields initialized.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="da1ae-102">Der Typ des Elements Telemetrie.</span><span class="sxs-lookup"><span data-stu-id="da1ae-102">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="da1ae-103">Telemetrie-Clientobjekt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-103">Telemetry client object.</span></span></param>
        <param name="operationName"><span data-ttu-id="da1ae-104">Name des Vorgangs plant diesen Kunden weitergeben.</span><span class="sxs-lookup"><span data-stu-id="da1ae-104">Name of the operation that customer is planning to propagate.</span></span></param>
        <summary>
            <span data-ttu-id="da1ae-105">Startvorgang erstellt ein Objekt der Vorgang mit einem entsprechenden Telemetrie-Element.</span><span class="sxs-lookup"><span data-stu-id="da1ae-105">Start operation creates an operation object with a respective telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="da1ae-106">Vorgangs-Objekt durch ein neues Telemetrie-Element, das mit der aktuellen Startzeit und Timestamp.</span><span class="sxs-lookup"><span data-stu-id="da1ae-106">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, T operationTelemetry) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, !!T operationTelemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,``0)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * 'T -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationTelemetry)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationTelemetry" Type="T" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="da1ae-107">Der Typ des Elements Telemetrie.</span><span class="sxs-lookup"><span data-stu-id="da1ae-107">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="da1ae-108">Telemetrie-Clientobjekt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-108">Telemetry client object.</span></span></param>
        <param name="operationTelemetry"><span data-ttu-id="da1ae-109">Der Vorgang zum Starten.</span><span class="sxs-lookup"><span data-stu-id="da1ae-109">Operation to start.</span></span></param>
        <summary>
            <span data-ttu-id="da1ae-110">Erstellt ein Objekt der Vorgang mit einem bestimmten Telemetrie-Element.</span><span class="sxs-lookup"><span data-stu-id="da1ae-110">Creates an operation object with a given telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="da1ae-111">Vorgangs-Objekt durch ein neues Telemetrie-Element, das mit der aktuellen Startzeit und Timestamp.</span><span class="sxs-lookup"><span data-stu-id="da1ae-111">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; StartOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId = null) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetrynew();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; StartOperation&lt;.ctor (class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, string operationName, string operationId, string parentOperationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation``1(Microsoft.ApplicationInsights.TelemetryClient,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member StartOperation : Microsoft.ApplicationInsights.TelemetryClient * string * string * string -&gt; Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))&gt; (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry and 'T : (new : unit -&gt; 'T))" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StartOperation (telemetryClient, operationName, operationId, parentOperationId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operationName" Type="System.String" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="parentOperationId" Type="System.String" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="da1ae-112">Der Typ des Elements Telemetrie.</span><span class="sxs-lookup"><span data-stu-id="da1ae-112">Type of the telemetry item.</span></span></typeparam>
        <param name="telemetryClient"><span data-ttu-id="da1ae-113">Telemetrie-Clientobjekt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-113">Telemetry client object.</span></span></param>
        <param name="operationName"><span data-ttu-id="da1ae-114">Name des Vorgangs plant diesen Kunden weitergeben.</span><span class="sxs-lookup"><span data-stu-id="da1ae-114">Name of the operation that customer is planning to propagate.</span></span></param>
        <param name="operationId"><span data-ttu-id="da1ae-115">Vorgangs-ID in den neuen Vorgang festgelegt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-115">Operation ID to set in the new operation.</span></span></param>
        <param name="parentOperationId"><span data-ttu-id="da1ae-116">Optionaler übergeordneter Vorgangs-ID in den neuen Vorgang festgelegt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-116">Optional parent operation ID to set in the new operation.</span></span></param>
        <summary>
            <span data-ttu-id="da1ae-117">Startvorgang erstellt ein Objekt der Vorgang mit einem entsprechenden Telemetrie-Element.</span><span class="sxs-lookup"><span data-stu-id="da1ae-117">Start operation creates an operation object with a respective telemetry item.</span></span> 
            </summary>
        <returns><span data-ttu-id="da1ae-118">Vorgangs-Objekt durch ein neues Telemetrie-Element, das mit der aktuellen Startzeit und Timestamp.</span><span class="sxs-lookup"><span data-stu-id="da1ae-118">Operation item object with a new telemetry item having current start time and timestamp.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopOperation&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static void StopOperation&lt;T&gt; (this Microsoft.ApplicationInsights.TelemetryClient telemetryClient, Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt; operation) where T : Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void StopOperation&lt;(class Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry) T&gt;(class Microsoft.ApplicationInsights.TelemetryClient telemetryClient, class Microsoft.ApplicationInsights.Extensibility.IOperationHolder`1&lt;!!T&gt; operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation``1(Microsoft.ApplicationInsights.TelemetryClient,Microsoft.ApplicationInsights.Extensibility.IOperationHolder{``0})" />
      <MemberSignature Language="F#" Value="static member StopOperation : Microsoft.ApplicationInsights.TelemetryClient * Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;'T (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)&gt; -&gt; unit (requires 'T :&gt; Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry)" Usage="Microsoft.ApplicationInsights.TelemetryClientExtensions.StopOperation (telemetryClient, operation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <BaseTypeName>Microsoft.ApplicationInsights.Extensibility.Implementation.OperationTelemetry</BaseTypeName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="telemetryClient" Type="Microsoft.ApplicationInsights.TelemetryClient" RefType="this" />
        <Parameter Name="operation" Type="Microsoft.ApplicationInsights.Extensibility.IOperationHolder&lt;T&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="telemetryClient"><span data-ttu-id="da1ae-119">Telemetrie-Clientobjekt.</span><span class="sxs-lookup"><span data-stu-id="da1ae-119">Telemetry client object.</span></span></param>
        <param name="operation"><span data-ttu-id="da1ae-120">Vorgangs-Objekt, das Berechnen der Dauer und nachverfolgen.</span><span class="sxs-lookup"><span data-stu-id="da1ae-120">Operation object to compute duration and track.</span></span></param>
        <summary>
            <span data-ttu-id="da1ae-121">"Stop"-Vorgang die Dauer des Vorgangs berechnet und verfolgt mithilfe des jeweiligen Telemetrie-Clients.</span><span class="sxs-lookup"><span data-stu-id="da1ae-121">Stop operation computes the duration of the operation and tracks it using the respective telemetry client.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>