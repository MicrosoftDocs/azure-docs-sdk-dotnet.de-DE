<Type Name="IServiceRemotingResponseMessageBody" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingResponseMessageBody" />
  <TypeSignature Language="F#" Value="type IServiceRemotingResponseMessageBody = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Schnittstelle, die implementiert werden muss, um Remoteanforderungen Nachrichtentext der Antwort bereit.
            Den Rückgabetyp von einem Remoting-Methode enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public object Get (Type paramType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object Get(class System.Type paramType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody.Get(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Function Get (paramType As Type) As Object" />
      <MemberSignature Language="F#" Value="abstract member Get : Type -&gt; obj" Usage="iServiceRemotingResponseMessageBody.Get paramType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="paramType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="paramType"> Der Rückgabetyp einer Remoting-Methode</param>
        <summary>
            Ruft die Antwort von einem Remoting-Methode von einem Remoting-Antworttext vor dem Senden an den Client ab. 
            </summary>
        <returns>Antwort der Remoting-Methode</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Set">
      <MemberSignature Language="C#" Value="public void Set (object response);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Set(object response) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody.Set(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Set (response As Object)" />
      <MemberSignature Language="F#" Value="abstract member Set : obj -&gt; unit" Usage="iServiceRemotingResponseMessageBody.Set response" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="response" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="response">Antwort der Remoting-Methode</param>
        <summary>
            Legt die Antwort von einem Remoting-Methode in einer Antwort Remoting Text
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>