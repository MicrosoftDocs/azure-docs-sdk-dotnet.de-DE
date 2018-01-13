<Type Name="ClientRequestIdProvider" FullName="Microsoft.Azure.Batch.ClientRequestIdProvider">
  <TypeSignature Language="C#" Value="public class ClientRequestIdProvider : Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClientRequestIdProvider extends Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ClientRequestIdProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class ClientRequestIdProvider&#xA;Inherits RequestInterceptor" />
  <TypeSignature Language="F#" Value="type ClientRequestIdProvider = class&#xA;    inherit RequestInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält eine Funktion zum Generieren einer Clientanforderungs-Id für die festzulegende als Interceptor <see cref="P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId" />.
            Wenn mehrere dieses Instanzen Festlegen der letzten Wins.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientRequestIdProvider (Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,Guid&gt; generateClientRequestIdFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class Microsoft.Azure.Batch.Protocol.IBatchRequest, valuetype System.Guid&gt; generateClientRequestIdFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ClientRequestIdProvider.#ctor(System.Func{Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (generateClientRequestIdFunc As Func(Of IBatchRequest, Guid))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ClientRequestIdProvider : Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest, Guid&gt; -&gt; Microsoft.Azure.Batch.ClientRequestIdProvider" Usage="new Microsoft.Azure.Batch.ClientRequestIdProvider generateClientRequestIdFunc" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="generateClientRequestIdFunc" Type="System.Func&lt;Microsoft.Azure.Batch.Protocol.IBatchRequest,System.Guid&gt;" />
      </Parameters>
      <Docs>
        <param name="generateClientRequestIdFunc">
            Eine Funktion verwendet, um die Clientanforderungs-Id zu generieren.  Diese Funktion kann für einen bestimmten Vorgang aufgrund von Wiederholungsversuchen mehr als einmal aufgerufen werden.
            </param>
        <summary>
            Initialisiert eine neue <see cref="T:Microsoft.Azure.Batch.ClientRequestIdProvider" /> für die Verwendung in Client-Anforderungs-Id der Anforderung festlegen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>