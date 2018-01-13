<Type Name="RequestInterceptor" FullName="Microsoft.Azure.Batch.Protocol.RequestInterceptor">
  <TypeSignature Language="C#" Value="public class RequestInterceptor : Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RequestInterceptor extends Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.RequestInterceptor" />
  <TypeSignature Language="VB.NET" Value="Public Class RequestInterceptor&#xA;Inherits RequestReplacementInterceptor" />
  <TypeSignature Language="F#" Value="type RequestInterceptor = class&#xA;    inherit RequestReplacementInterceptor" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.RequestReplacementInterceptor</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Diese Klasse ermöglicht einen Interceptor zu überprüfen, zu ändern oder zu ignorieren einer <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestInterceptor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestInterceptor.#ctor" />
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
            Initialisiert eine neue Instanz der RequestInterceptor an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RequestInterceptor (Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler interceptor);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler interceptor) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.RequestInterceptor.#ctor(Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (interceptor As BatchRequestModificationInterceptHandler)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.RequestInterceptor : Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler -&gt; Microsoft.Azure.Batch.Protocol.RequestInterceptor" Usage="new Microsoft.Azure.Batch.Protocol.RequestInterceptor interceptor" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="interceptor" Type="Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler" />
      </Parameters>
      <Docs>
        <param name="interceptor">Ein Delegat, der zugelassen wird, um zu überprüfen, ändern oder eine BatchRequest ignorieren.</param>
        <summary>
            Initialisiert eine neue Instanz der RequestInterceptor, die einen bestimmten BatchRequestModificationInterceptHandler aufruft.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModificationInterceptHandler">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler ModificationInterceptHandler { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler ModificationInterceptHandler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.RequestInterceptor.ModificationInterceptHandler" />
      <MemberSignature Language="VB.NET" Value="Public Property ModificationInterceptHandler As BatchRequestModificationInterceptHandler" />
      <MemberSignature Language="F#" Value="member this.ModificationInterceptHandler : Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler with get, set" Usage="Microsoft.Azure.Batch.Protocol.RequestInterceptor.ModificationInterceptHandler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.BatchRequestModificationInterceptHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die BatchRequestModificationInterceptHandler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>