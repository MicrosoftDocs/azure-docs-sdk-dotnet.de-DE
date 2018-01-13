<Type Name="RequestInformation" FullName="Microsoft.Azure.Batch.Common.RequestInformation">
  <TypeSignature Language="C#" Value="public class RequestInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.RequestInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestInformation" />
  <TypeSignature Language="F#" Value="type RequestInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Reihe von allgemeinen Informationen, die mit einer Anforderung verknüpft ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.RequestInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.BatchError BatchError { get; protected internal set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.BatchError BatchError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestInformation.BatchError" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchError As BatchError" />
      <MemberSignature Language="F#" Value="member this.BatchError : Microsoft.Azure.Batch.BatchError with get, set" Usage="Microsoft.Azure.Batch.Common.RequestInformation.BatchError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Batch-Fehlerinformationen enthält ausführliche Metadaten eines bestimmten Fehlers aufgetreten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; protected internal set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestInformation.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Common.RequestInformation.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Clientanforderungs-Id vom Client festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Net.HttpStatusCode&gt; HttpStatusCode { get; protected internal set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Net.HttpStatusCode&gt; HttpStatusCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestInformation.HttpStatusCode" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusCode As Nullable(Of HttpStatusCode)" />
      <MemberSignature Language="F#" Value="member this.HttpStatusCode : Nullable&lt;System.Net.HttpStatusCode&gt; with get, set" Usage="Microsoft.Azure.Batch.Common.RequestInformation.HttpStatusCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Net.HttpStatusCode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den HTTP-Statuscode für die Anforderung fest.
            In Fällen, in dem eine HTTP-Antwort nie (z. B. auf clientseitiges Timeout empfangen wurde) für diese Eigenschaft null ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpStatusMessage">
      <MemberSignature Language="C#" Value="public string HttpStatusMessage { get; protected internal set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HttpStatusMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestInformation.HttpStatusMessage" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpStatusMessage As String" />
      <MemberSignature Language="F#" Value="member this.HttpStatusMessage : string with get, set" Usage="Microsoft.Azure.Batch.Common.RequestInformation.HttpStatusMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die HTTP-Statusnachricht für die Anforderung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestId">
      <MemberSignature Language="C#" Value="public string ServiceRequestId { get; protected internal set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RequestInformation.ServiceRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestId : string with get, set" Usage="Microsoft.Azure.Batch.Common.RequestInformation.ServiceRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die dienstanforderungs-ID für diese Anforderung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>