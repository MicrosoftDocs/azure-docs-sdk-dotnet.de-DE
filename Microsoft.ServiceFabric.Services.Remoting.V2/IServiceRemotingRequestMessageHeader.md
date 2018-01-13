<Type Name="IServiceRemotingRequestMessageHeader" FullName="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader">
  <TypeSignature Language="C#" Value="public interface IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceRemotingRequestMessageHeader" />
  <TypeSignature Language="F#" Value="type IServiceRemotingRequestMessageHeader = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c31e0-101">Gibt die Header an, die zusammen mit einer Meldung ServiceRemoting gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="c31e0-101">Specifies the headers that are sent along with a ServiceRemoting message.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddHeader">
      <MemberSignature Language="C#" Value="public void AddHeader (string headerName, byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void AddHeader(string headerName, unsigned int8[] headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.AddHeader(System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddHeader (headerName As String, headerValue As Byte())" />
      <MemberSignature Language="F#" Value="abstract member AddHeader : string * byte[] -&gt; unit" Usage="iServiceRemotingRequestMessageHeader.AddHeader (headerName, headerValue)" />
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
        <param name="headerName"><span data-ttu-id="c31e0-102">Der Name-Header.</span><span class="sxs-lookup"><span data-stu-id="c31e0-102">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="c31e0-103">Der Headerwert.</span><span class="sxs-lookup"><span data-stu-id="c31e0-103">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="c31e0-104">Fügt einen neuen Header mit dem angegebenen Namen und Wert hinzu.</span><span class="sxs-lookup"><span data-stu-id="c31e0-104">Adds a new header with the specified name and value.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InterfaceId">
      <MemberSignature Language="C#" Value="public int InterfaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 InterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property InterfaceId As Integer" />
      <MemberSignature Language="F#" Value="member this.InterfaceId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c31e0-105">Ruft ab oder legt die Schnittstellen-Id der remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="c31e0-105">Gets or sets the interface id of the remote interface.</span></span>
            </summary>
        <value><span data-ttu-id="c31e0-106">Der Schnittstellen-Id.</span><span class="sxs-lookup"><span data-stu-id="c31e0-106">The interface id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvocationId">
      <MemberSignature Language="C#" Value="public string InvocationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InvocationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InvocationId" />
      <MemberSignature Language="VB.NET" Value="Public Property InvocationId As String" />
      <MemberSignature Language="F#" Value="member this.InvocationId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.InvocationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="InvocationId", Order=3)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c31e0-107">Ruft ab oder legt den Bezeichner für die remote-Methodenaufruf.</span><span class="sxs-lookup"><span data-stu-id="c31e0-107">Gets or sets the identifier for the remote method invocation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MethodId">
      <MemberSignature Language="C#" Value="public int MethodId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MethodId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.MethodId" />
      <MemberSignature Language="VB.NET" Value="Public Property MethodId As Integer" />
      <MemberSignature Language="F#" Value="member this.MethodId : int with get, set" Usage="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.MethodId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c31e0-108">Ruft ab, oder legt ihn fest MethodId der remote-Methode.</span><span class="sxs-lookup"><span data-stu-id="c31e0-108">Gets or sets the methodId of the remote method.</span></span>
            </summary>
        <value><span data-ttu-id="c31e0-109">Die Methoden-ID.</span><span class="sxs-lookup"><span data-stu-id="c31e0-109">The method id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetHeaderValue">
      <MemberSignature Language="C#" Value="public bool TryGetHeaderValue (string headerName, out byte[] headerValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryGetHeaderValue(string headerName, [out] unsigned int8[]&amp; headerValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageHeader.TryGetHeaderValue(System.String,System.Byte[]@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetHeaderValue (headerName As String, ByRef headerValue As Byte()) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryGetHeaderValue : string *  -&gt; bool" Usage="iServiceRemotingRequestMessageHeader.TryGetHeaderValue (headerName, headerValue)" />
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
        <param name="headerName"><span data-ttu-id="c31e0-110">Der Name-Header.</span><span class="sxs-lookup"><span data-stu-id="c31e0-110">The header Name.</span></span></param>
        <param name="headerValue"><span data-ttu-id="c31e0-111">Der Headerwert.</span><span class="sxs-lookup"><span data-stu-id="c31e0-111">The header value.</span></span></param>
        <summary>
            <span data-ttu-id="c31e0-112">Ruft den Header mit dem angegebenen Namen ab.</span><span class="sxs-lookup"><span data-stu-id="c31e0-112">Gets the header with the specified name.</span></span>
            </summary>
        <returns><span data-ttu-id="c31e0-113">"true", wenn ein Header mit diesem Namen vorhanden ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="c31e0-113">true if a header with that name exists; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>