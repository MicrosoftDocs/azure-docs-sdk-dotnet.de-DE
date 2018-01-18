<Type Name="RemotingListener" FullName="Microsoft.ServiceFabric.Services.Remoting.RemotingListener">
  <TypeSignature Language="C#" Value="public enum RemotingListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RemotingListener extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.RemotingListener" />
  <TypeSignature Language="VB.NET" Value="Public Enum RemotingListener" />
  <TypeSignature Language="F#" Value="type RemotingListener = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="301e8-101">Bestimmt den Remoting-Stapel für Server-Listener, Verwendung von Remoting Anbieter Attribuite den Remoting-Client zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="301e8-101">Determines the remoting stack for server/listener when using remoting provider attribuite to determine the remoting client.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CompatListener">
      <MemberSignature Language="C#" Value="CompatListener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener CompatListener = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.CompatListener" />
      <MemberSignature Language="VB.NET" Value="CompatListener" />
      <MemberSignature Language="F#" Value="CompatListener = 1" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.CompatListener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-102">Diese Option ist zum Erstellen von Netzwerklistener erstellt sowohl V1 und V2-Listener zur Unterstützung von V1 und V2-Clients aktiviert.</span><span class="sxs-lookup"><span data-stu-id="301e8-102">This is selected to create Listener which creates both V1 and V2 Listener to support both V1 and V2 Clients.</span></span>
            <span data-ttu-id="301e8-103">Dies ist hilfreich bei einem Upgrade von V1, V2-Listener.</span><span class="sxs-lookup"><span data-stu-id="301e8-103">This is useful in case of upgrade from V1 to V2 Listener.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="V1Listener">
      <MemberSignature Language="C#" Value="V1Listener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener V1Listener = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V1Listener" />
      <MemberSignature Language="VB.NET" Value="V1Listener" />
      <MemberSignature Language="F#" Value="V1Listener = 0" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V1Listener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-104">Diese Option ist aktiviert, erstellen Sie V1 Listener.V2 ist eine alte (bald zu als veraltet markiert) Remoting-Stapel.</span><span class="sxs-lookup"><span data-stu-id="301e8-104">This is selected to create V1 Listener.V2 is a old(soon to be deprecated) Remoting Stack.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="V2Listener">
      <MemberSignature Language="C#" Value="V2Listener" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Services.Remoting.RemotingListener V2Listener = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V2Listener" />
      <MemberSignature Language="VB.NET" Value="V2Listener" />
      <MemberSignature Language="F#" Value="V2Listener = 2" Usage="Microsoft.ServiceFabric.Services.Remoting.RemotingListener.V2Listener" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.RemotingListener</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-105">Diese Option ist aktiviert, erstellen Sie V2 Listener.V2 besteht aus einem neuen Remoting-Stapel.</span><span class="sxs-lookup"><span data-stu-id="301e8-105">This is selected to create V2 Listener.V2 is a new Remoting Stack.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>