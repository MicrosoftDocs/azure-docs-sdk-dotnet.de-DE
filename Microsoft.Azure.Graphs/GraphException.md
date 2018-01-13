<Type Name="GraphException" FullName="Microsoft.Azure.Graphs.GraphException">
  <TypeSignature Language="C#" Value="public class GraphException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit GraphException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Graphs.GraphException" />
  <TypeSignature Language="VB.NET" Value="Public Class GraphException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type GraphException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
    <AssemblyVersion>1.14.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c80d0-101">Basisklasse für alle Ausnahmen für die Graph-Bibliothek mit Fokus</span><span class="sxs-lookup"><span data-stu-id="c80d0-101">Base class for any graph library-focused exceptions</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphException innerException, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Graphs.GraphException innerException, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphException,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (innerException As GraphException, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphException * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (innerException, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="innerException" Type="Microsoft.Azure.Graphs.GraphException" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="innerException"></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="c80d0-102">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="c80d0-102">Constructor.</span></span> <span data-ttu-id="c80d0-103">Verwenden Sie es für Problemen auf dem Server, wenn eine interne Ausnahme wurde abgefangen, und wir benötigen, um es zu umschließen.</span><span class="sxs-lookup"><span data-stu-id="c80d0-103">Use it for server side issues when an inner exception was caught and we need to wrap it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphStatusCode errorCode, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Graphs.GraphStatusCode errorCode, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphStatusCode,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As GraphStatusCode, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphStatusCode * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (errorCode, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.Azure.Graphs.GraphStatusCode" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="c80d0-104">Fehlercode entspricht HTTP-RFC 2616</span><span class="sxs-lookup"><span data-stu-id="c80d0-104">error code, matches HTTP RFC 2616</span></span></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="c80d0-105">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="c80d0-105">Constructor.</span></span> <span data-ttu-id="c80d0-106">Verwenden Sie diese Option, wenn keine innere Ausnahme für die (z. B. externe) zur Verfügung steht.</span><span class="sxs-lookup"><span data-stu-id="c80d0-106">Use it when no inner (e.g. external) exception is available.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GraphException (Microsoft.Azure.Graphs.GraphStatusCode errorCode, Exception innerException, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Graphs.GraphStatusCode errorCode, class System.Exception innerException, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.#ctor(Microsoft.Azure.Graphs.GraphStatusCode,System.Exception,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (errorCode As GraphStatusCode, innerException As Exception, message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Graphs.GraphException : Microsoft.Azure.Graphs.GraphStatusCode * Exception * string -&gt; Microsoft.Azure.Graphs.GraphException" Usage="new Microsoft.Azure.Graphs.GraphException (errorCode, innerException, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="errorCode" Type="Microsoft.Azure.Graphs.GraphStatusCode" />
        <Parameter Name="innerException" Type="System.Exception" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="errorCode"><span data-ttu-id="c80d0-107">Fehlercode entspricht HTTP-RFC 2616</span><span class="sxs-lookup"><span data-stu-id="c80d0-107">error code, matches HTTP RFC 2616</span></span></param>
        <param name="innerException"></param>
        <param name="message"></param>
        <summary>
            <span data-ttu-id="c80d0-108">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="c80d0-108">Constructor.</span></span> <span data-ttu-id="c80d0-109">Verwenden Sie es aus, wenn eine interne Ausnahme wurde abgefangen, und wir benötigen, um es zu umschließen.</span><span class="sxs-lookup"><span data-stu-id="c80d0-109">Use it when an inner exception was caught and we need to wrap it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public string Context { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.Context" />
      <MemberSignature Language="VB.NET" Value="Public Property Context As String" />
      <MemberSignature Language="F#" Value="member this.Context : string with get, set" Usage="Microsoft.Azure.Graphs.GraphException.Context" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c80d0-110">Aktuelle externe Verbindung (oder externe Ausführungskontext) Namen, wie durch den Aufrufer festgelegt</span><span class="sxs-lookup"><span data-stu-id="c80d0-110">Current external connection (or external execution context) name, as set by the caller</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Graphs.GraphStatusCode ErrorCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Graphs.GraphStatusCode ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ErrorCode As GraphStatusCode" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Microsoft.Azure.Graphs.GraphStatusCode with get, set" Usage="Microsoft.Azure.Graphs.GraphException.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Graphs.GraphStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c80d0-111">Der Ausnahme zugeordneten Fehlercode.</span><span class="sxs-lookup"><span data-stu-id="c80d0-111">Error code associated with the exception.</span></span>
            <span data-ttu-id="c80d0-112">Semantische für Graph-Fehlercodes in Tinkerpop des Anbieter-Dokumentation beschrieben wird: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements allgemeine Details zur HTTP-Fehlercodes wie in RFC 2615: http:/ /www.w3.org/Protocols/rfc2616/rfc2616-sec10.HTML</span><span class="sxs-lookup"><span data-stu-id="c80d0-112">Semantic for graph error codes is described in tinkerpop's provider documentation: http://tinkerpop.apache.org/docs/current/dev/provider/#_graph_driver_provider_requirements General detail regarding HTTP Error codes as described by RFC 2615: http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frame">
      <MemberSignature Language="C#" Value="public string Frame { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frame" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.Frame" />
      <MemberSignature Language="VB.NET" Value="Public Property Frame As String" />
      <MemberSignature Language="F#" Value="member this.Frame : string with get, set" Usage="Microsoft.Azure.Graphs.GraphException.Frame" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c80d0-113">Aktuellen logischen Frame (Name der innersten Ausführungsbereichs)</span><span class="sxs-lookup"><span data-stu-id="c80d0-113">Current logical frame (name of innermost execution scope)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Guid RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Graphs.GraphException.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Guid" />
      <MemberSignature Language="F#" Value="member this.RequestId : Guid with get, set" Usage="Microsoft.Azure.Graphs.GraphException.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c80d0-114">Eindeutige Bezeichner (optional durch den Aufrufer Clientcode bereitgestellt) für die Anforderung der Ausführung im Moment, wenn die Ausnahme erstellt/ausgelöst wurde, zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c80d0-114">Unique identifier (optionally provided by the client caller code) for the request associated with the execution at the moment when the exception was created/thrown.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Graphs.GraphException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="graphException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Graphs</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
        <AssemblyVersion>1.14.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c80d0-115">Konvertiert eine Ausnahme in eine Anzeigezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c80d0-115">Converts an exception to a display string.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>