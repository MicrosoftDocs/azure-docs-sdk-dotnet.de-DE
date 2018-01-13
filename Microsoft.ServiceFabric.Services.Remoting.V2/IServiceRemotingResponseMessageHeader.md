<Type Name="IServiceRemotingResponseMessageHeader" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingResponseMessageHeader" />
  <TypeSignature Language="F#" Value="type IServiceRemotingResponseMessageHeader = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd471-101">Definiert ein Schnittstellen, die implementiert werden müssen, um Remoting-Antwortnachricht Header verliehen wird.</span><span class="sxs-lookup"><span data-stu-id="fd471-101">Defines an interfaces that must be implemented to provide header for remoting response message.</span></span>
            
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddHeader">
      <MemberSignature Language="C#" Value="public void AddHeader (string headerName, byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddHeader(string headerName, unsigned int8[] headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader.AddHeader(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddHeader (headerName As String, headerValue As Byte())" />
      <MemberSignature Language="F#" Value="abstract member AddHeader : string * byte[] -&gt; unit" Usage="iServiceRemotingResponseMessageHeader.AddHeader (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="headerName"><span data-ttu-id="fd471-102">Der Name-Header.</span><span class="sxs-lookup"><span data-stu-id="fd471-102">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="fd471-103">Der Headerwert.</span><span class="sxs-lookup"><span data-stu-id="fd471-103">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="fd471-104">Fügt einen neuen Header mit dem angegebenen Namen und Wert hinzu.</span><span class="sxs-lookup"><span data-stu-id="fd471-104">Adds a new header with the specified name and value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetHeaderValue">
      <MemberSignature Language="C#" Value="public bool TryGetHeaderValue (string headerName, out byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetHeaderValue(string headerName, [out] unsigned int8[]&amp; headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageHeader.TryGetHeaderValue(System.String,System.Byte[]@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetHeaderValue (headerName As String, ByRef headerValue As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetHeaderValue : string *  -&gt; bool" Usage="iServiceRemotingResponseMessageHeader.TryGetHeaderValue (headerName, headerValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="headerName" Type="System.String" />
        <Parameter Name="headerValue" Type="System.Byte[]&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="headerName"><span data-ttu-id="fd471-105">Der Name-Header.</span><span class="sxs-lookup"><span data-stu-id="fd471-105">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="fd471-106">Der Headerwert.</span><span class="sxs-lookup"><span data-stu-id="fd471-106">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="fd471-107">Ruft den Header mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="fd471-107">Gets the header with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="fd471-108">"true", wenn ein Header mit diesem Namen vorhanden ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="fd471-108">true if a header with that name exists; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>