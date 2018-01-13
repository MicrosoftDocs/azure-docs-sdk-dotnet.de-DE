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
            Ausnahme, die vom Client zurückgegeben. Sie kapselt alle remote Excepotion Merry Server, Unhandled und behandelten Ausnahme.
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
            Die Ausnahme verarbeitet Fehler
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
            Nicht behandelte Ausnahme
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
            Verlauf der Ausnahme alle Wiederholungen für diesen Vorgang. Dies sollte nicht für jede Wiederholung zurückgesetzt werden
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
            HTTP-Nachricht
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
            HttpStatus-code
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
            Letzte Aufruf Latenz
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
            Vom Server für die letzte HTTP-Anforderung für diesen Vorgang zurückgegebenen Remote Ausnahme Java-Klassenname
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
            Remote Ausnahmemeldung, die vom Server für die letzte HTTP-Anforderung für diesen Vorgang zurückgegebenen
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
            Remote Ausnahmename des Servers für die letzten HTTP-Anforderung für diesen Vorgang zurückgegeben
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
            Gesamtanzahl der Wiederholungen
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
            Ablaufverfolgungs-Id vom Server zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>