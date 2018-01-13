<Type Name="PoolDeleteHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders">
  <TypeSignature Language="C#" Value="public class PoolDeleteHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolDeleteHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolDeleteHeaders" />
  <TypeSignature Language="F#" Value="type PoolDeleteHeaders = class" />
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
            Definiert die Header für den Löschvorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolDeleteHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PoolDeleteHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolDeleteHeaders (string clientRequestId = null, string requestId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientRequestId, string requestId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As String = null, Optional requestId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders (clientRequestId, requestId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.String" />
        <Parameter Name="requestId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientRequestId">Die Client-Request-Id vom Client bereitgestellt wird, während der Anforderung. Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".</param>
        <param name="requestId">Ein eindeutiger Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde. Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden. Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.</param>
        <summary>
            Initialisiert eine neue Instanz der PoolDeleteHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public string ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As String" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="client-request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die vom Client bei der Anforderung angegebene Client-Request-Id. Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public string RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As String" />
      <MemberSignature Language="F#" Value="member this.RequestId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolDeleteHeaders.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert einen eindeutigen Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde. Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden. Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>