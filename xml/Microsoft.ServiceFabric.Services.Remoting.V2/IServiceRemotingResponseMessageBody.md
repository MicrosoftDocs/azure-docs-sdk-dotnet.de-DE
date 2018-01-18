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
            <span data-ttu-id="382f6-101">Definiert die Schnittstelle, die implementiert werden muss, um Remoteanforderungen Nachrichtentext der Antwort bereit.</span><span class="sxs-lookup"><span data-stu-id="382f6-101">Defines the interface that must be implemented to provide Response Message Body for remoting requests .</span></span>
            <span data-ttu-id="382f6-102">Den Rückgabetyp von einem Remoting-Methode enthält.</span><span class="sxs-lookup"><span data-stu-id="382f6-102">This contains the return Type of a remoting Method.</span></span>
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
        <param name="paramType"> <span data-ttu-id="382f6-103">Der Rückgabetyp einer Remoting-Methode</span><span class="sxs-lookup"><span data-stu-id="382f6-103">Return Type of a Remoting Method</span></span></param>
        <summary>
            <span data-ttu-id="382f6-104">Ruft die Antwort von einem Remoting-Methode von einem Remoting-Antworttext vor dem Senden an den Client ab.</span><span class="sxs-lookup"><span data-stu-id="382f6-104">Gets the response of a remoting Method from a remoting response body before sending it to Client.</span></span> 
            </summary>
        <returns><span data-ttu-id="382f6-105">Antwort der Remoting-Methode</span><span class="sxs-lookup"><span data-stu-id="382f6-105">Remoting Method Response</span></span></returns>
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
        <param name="response"><span data-ttu-id="382f6-106">Antwort der Remoting-Methode</span><span class="sxs-lookup"><span data-stu-id="382f6-106">Remoting Method Response</span></span></param>
        <summary>
            <span data-ttu-id="382f6-107">Legt die Antwort von einem Remoting-Methode in einer Antwort Remoting Text</span><span class="sxs-lookup"><span data-stu-id="382f6-107">Sets the response of a remoting Method in a remoting response Body</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>