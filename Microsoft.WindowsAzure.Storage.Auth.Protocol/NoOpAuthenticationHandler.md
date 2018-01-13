<Type Name="NoOpAuthenticationHandler" FullName="Microsoft.WindowsAzure.Storage.Auth.Protocol.NoOpAuthenticationHandler">
  <TypeSignature Language="C#" Value="public sealed class NoOpAuthenticationHandler : Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NoOpAuthenticationHandler extends System.Object implements class Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.NoOpAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NoOpAuthenticationHandler&#xA;Implements IAuthenticationHandler" />
  <TypeSignature Language="F#" Value="type NoOpAuthenticationHandler = class&#xA;    interface IAuthenticationHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt einen Handler, der die HTTP-Anforderungen mit keine Authentifizierungsinformationen signiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NoOpAuthenticationHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.NoOpAuthenticationHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Auth.Protocol.NoOpAuthenticationHandler" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignRequest">
      <MemberSignature Language="C#" Value="public void SignRequest (System.Net.HttpWebRequest request, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SignRequest(class System.Net.HttpWebRequest request, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Auth.Protocol.NoOpAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SignRequest : System.Net.HttpWebRequest * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="noOpAuthenticationHandler.SignRequest (request, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Auth.Protocol.IAuthenticationHandler.SignRequest(System.Net.HttpWebRequest,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.HttpWebRequest" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="request">Die zum Signieren von HTTP-Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Signiert die angegebene HTTP-Anforderung mit den keine Authentifizierungsinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>