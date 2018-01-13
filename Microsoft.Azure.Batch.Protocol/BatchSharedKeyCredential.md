<Type Name="BatchSharedKeyCredential" FullName="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential">
  <TypeSignature Language="C#" Value="public class BatchSharedKeyCredential : Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchSharedKeyCredential extends Microsoft.Rest.ServiceClientCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchSharedKeyCredential&#xA;Inherits ServiceClientCredentials" />
  <TypeSignature Language="F#" Value="type BatchSharedKeyCredential = class&#xA;    inherit ServiceClientCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClientCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Gemeinsam genutzter Schlüssel Anmeldeinformationen für ein Azure Batch-Konto ein.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchSharedKeyCredential (string accountName, string keyValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountName, string keyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (accountName As String, keyValue As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential : string * string -&gt; Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" Usage="new Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential (accountName, keyValue)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountName" Type="System.String" />
        <Parameter Name="keyValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountName">Der Name des Batch-Konto.</param>
        <param name="keyValue">Der Zugriffsschlüssel für das Batch-Konto als Base64-codierte Zeichenfolge.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountName">
      <MemberSignature Language="C#" Value="public string AccountName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountName As String" />
      <MemberSignature Language="F#" Value="member this.AccountName : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.AccountName" />
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
            Ruft die Batch-Kontoname.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValue">
      <MemberSignature Language="C#" Value="public string KeyValue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValue As String" />
      <MemberSignature Language="F#" Value="member this.KeyValue : string" Usage="Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.KeyValue" />
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
            Ruft den Zugriffsschlüssel als Base64-codierte Zeichenfolge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessHttpRequestAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task ProcessHttpRequestAsync (System.Net.Http.HttpRequestMessage httpRequest, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task ProcessHttpRequestAsync(class System.Net.Http.HttpRequestMessage httpRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchSharedKeyCredential.ProcessHttpRequestAsync(System.Net.Http.HttpRequestMessage,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.ProcessHttpRequestAsync : System.Net.Http.HttpRequestMessage * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="batchSharedKeyCredential.ProcessHttpRequestAsync (httpRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpRequest" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="httpRequest">Die HTTP-Anforderung</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Anforderung.</param>
        <summary>
            Signiert eine HTTP-Anforderung mit den aktuellen Anmeldeinformationen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" /> , das Signaturzertifikat asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>