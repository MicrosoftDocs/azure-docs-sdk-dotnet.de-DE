<Type Name="ResponseInterceptor" FullName="Microsoft.Azure.Batch.Protocol.ResponseInterceptor">
  <TypeSignature Language="C#" Value="public class ResponseInterceptor : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResponseInterceptor extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ResponseInterceptor" />
  <TypeSignature Language="VB.NET" Value="Public Class ResponseInterceptor&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type ResponseInterceptor = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e7453-101">Eine BatchClientBehavior, die Überprüfung und Änderung von der BatchResponse ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="e7453-101">A BatchClientBehavior that enables inspection and modification of the BatchResponse.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResponseInterceptor (Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler responseInterceptHandler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.ResponseInterceptor/BatchResponseInterceptHandler responseInterceptHandler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ResponseInterceptor.#ctor(Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (responseInterceptHandler As ResponseInterceptor.BatchResponseInterceptHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.ResponseInterceptor : Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler -&gt; Microsoft.Azure.Batch.Protocol.ResponseInterceptor" Usage="new Microsoft.Azure.Batch.Protocol.ResponseInterceptor responseInterceptHandler" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="responseInterceptHandler" Type="Microsoft.Azure.Batch.Protocol.ResponseInterceptor+BatchResponseInterceptHandler" />
      </Parameters>
      <Docs>
        <param name="responseInterceptHandler"><span data-ttu-id="e7453-102">Die Methode für die abgefangene Antwort aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e7453-102">The method to invoke on the intercepted response.</span></span></param>
        <summary>
            <span data-ttu-id="e7453-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.ResponseInterceptor" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e7453-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.ResponseInterceptor" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResponseInterceptHandler">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler ResponseInterceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.ResponseInterceptor/BatchResponseInterceptHandler ResponseInterceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.ResponseInterceptor.ResponseInterceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ResponseInterceptHandler As ResponseInterceptor.BatchResponseInterceptHandler" />
      <MemberSignature Language="F#" Value="member this.ResponseInterceptHandler : Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler with get, set" Usage="Microsoft.Azure.Batch.Protocol.ResponseInterceptor.ResponseInterceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.ResponseInterceptor+BatchResponseInterceptHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e7453-104">Ruft ab oder legt die Methode für die abgefangene Antwort aufgerufen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e7453-104">Gets or sets the method to invoke on the intercepted response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>