<Type Name="AdlsException" FullName="Microsoft.Azure.DataLake.Store.AdlsException">
  <TypeSignature Language="C#" Value="public class AdlsException : System.IO.IOException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsException extends System.IO.IOException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.DataLake.Store.AdlsException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsException&#xA;Inherits IOException" />
  <TypeSignature Language="F#" Value="type AdlsException = class&#xA;    inherit IOException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
    <AssemblyVersion>0.1.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.IO.IOException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7e08d-101">Ausnahme, die vom Client zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7e08d-101">Exception returned by client.</span></span> <span data-ttu-id="7e08d-102">Sie kapselt alle remote Excepotion Merry Server, Unhandled und behandelten Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="7e08d-102">It encapsulates any remote excepotion returned from server, Unhandled and handled exception.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.DataLake.Store.AdlsException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.DataLake.Store.AdlsException : string -&gt; Microsoft.Azure.DataLake.Store.AdlsException" Usage="new Microsoft.Azure.DataLake.Store.AdlsException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-103">Die Ausnahme verarbeitet Fehler</span><span class="sxs-lookup"><span data-stu-id="7e08d-103">Handled exception errors</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ex">
      <MemberSignature Language="C#" Value="public Exception Ex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Ex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.Ex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Ex As Exception" />
      <MemberSignature Language="F#" Value="member this.Ex : Exception" Usage="Microsoft.Azure.DataLake.Store.AdlsException.Ex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-104">Nicht behandelte Ausnahme</span><span class="sxs-lookup"><span data-stu-id="7e08d-104">Unhandled exception</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionHistory">
      <MemberSignature Language="C#" Value="public string ExceptionHistory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionHistory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.ExceptionHistory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExceptionHistory As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionHistory : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.ExceptionHistory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-105">Verlauf der Ausnahme alle Wiederholungen für diesen Vorgang.</span><span class="sxs-lookup"><span data-stu-id="7e08d-105">Exception history of all the retries for this operation.</span></span> <span data-ttu-id="7e08d-106">Dies sollte nicht für jede Wiederholung zurückgesetzt werden</span><span class="sxs-lookup"><span data-stu-id="7e08d-106">This should not be reset for every retry</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpMessage">
      <MemberSignature Language="C#" Value="public string HttpMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.HttpMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpMessage As String" />
      <MemberSignature Language="F#" Value="member this.HttpMessage : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.HttpMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-107">HTTP-Nachricht</span><span class="sxs-lookup"><span data-stu-id="7e08d-107">Http message</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatus">
      <MemberSignature Language="C#" Value="public System.Net.HttpStatusCode HttpStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Net.HttpStatusCode HttpStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.HttpStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpStatus As HttpStatusCode" />
      <MemberSignature Language="F#" Value="member this.HttpStatus : System.Net.HttpStatusCode" Usage="Microsoft.Azure.DataLake.Store.AdlsException.HttpStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Net.HttpStatusCode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-108">HttpStatus-code</span><span class="sxs-lookup"><span data-stu-id="7e08d-108">HttpStatus code</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCallLatency">
      <MemberSignature Language="C#" Value="public long LastCallLatency { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastCallLatency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.LastCallLatency" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCallLatency As Long" />
      <MemberSignature Language="F#" Value="member this.LastCallLatency : int64" Usage="Microsoft.Azure.DataLake.Store.AdlsException.LastCallLatency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-109">Letzte Aufruf Latenz</span><span class="sxs-lookup"><span data-stu-id="7e08d-109">Last call latency</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionJavaClassName">
      <MemberSignature Language="C#" Value="public string RemoteExceptionJavaClassName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionJavaClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionJavaClassName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionJavaClassName As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionJavaClassName : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionJavaClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-110">Vom Server für die letzte HTTP-Anforderung für diesen Vorgang zurückgegebenen Remote Ausnahme Java-Klassenname</span><span class="sxs-lookup"><span data-stu-id="7e08d-110">Remote exception java classname returned from the server for the last Http request for this operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionMessage">
      <MemberSignature Language="C#" Value="public string RemoteExceptionMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionMessage As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionMessage : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-111">Remote Ausnahmemeldung, die vom Server für die letzte HTTP-Anforderung für diesen Vorgang zurückgegebenen</span><span class="sxs-lookup"><span data-stu-id="7e08d-111">Remote exception message returned from the server for the last Http request for this operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteExceptionName">
      <MemberSignature Language="C#" Value="public string RemoteExceptionName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RemoteExceptionName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteExceptionName As String" />
      <MemberSignature Language="F#" Value="member this.RemoteExceptionName : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.RemoteExceptionName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-112">Remote Ausnahmename des Servers für die letzten HTTP-Anforderung für diesen Vorgang zurückgegeben</span><span class="sxs-lookup"><span data-stu-id="7e08d-112">Remote exception name returned from the server for the last Http request for this operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retries">
      <MemberSignature Language="C#" Value="public int Retries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Retries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.Retries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Retries As Integer" />
      <MemberSignature Language="F#" Value="member this.Retries : int" Usage="Microsoft.Azure.DataLake.Store.AdlsException.Retries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-113">Gesamtanzahl der Wiederholungen</span><span class="sxs-lookup"><span data-stu-id="7e08d-113">Total number of retries</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TraceId">
      <MemberSignature Language="C#" Value="public string TraceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TraceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.DataLake.Store.AdlsException.TraceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TraceId As String" />
      <MemberSignature Language="F#" Value="member this.TraceId : string" Usage="Microsoft.Azure.DataLake.Store.AdlsException.TraceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DataLake.Store</AssemblyName>
        <AssemblyVersion>0.1.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e08d-114">Ablaufverfolgungs-Id vom Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7e08d-114">Trace Id as returned by server</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>