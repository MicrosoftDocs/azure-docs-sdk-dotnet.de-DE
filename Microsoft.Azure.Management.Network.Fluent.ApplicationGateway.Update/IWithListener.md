<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7e270-101">Die Phase von einer Anwendung Gateway Update ermöglicht Front-End-Listener ändern.</span><span class="sxs-lookup"><span data-stu-id="7e270-101">The stage of an application gateway update allowing to modify frontend listeners.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.DefineListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineListener (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithListener.DefineListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7e270-102">Ein eindeutiger Name für den Listener.</span><span class="sxs-lookup"><span data-stu-id="7e270-102">A unique name for the listener.</span></span></param>
        <summary>
            <span data-ttu-id="7e270-103">Beginn der Definition einer neuen Anwendung Gateway Listener an das Gateway angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="7e270-103">Begins the definition of a new application gateway listener to be attached to the gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7e270-104">Die erste Phase der Definition des Listeners.</span><span class="sxs-lookup"><span data-stu-id="7e270-104">The first stage of the listener definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate UpdateListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.UpdateListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate" Usage="iWithListener.UpdateListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7e270-105">Der Name eines vorhanden Listeners aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7e270-105">The name of an existing listener to update.</span></span></param>
        <summary>
            <span data-ttu-id="7e270-106">Startet das Update eines Listeners.</span><span class="sxs-lookup"><span data-stu-id="7e270-106">Begins the update of a listener.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7e270-107">Die nächste Phase der Definition oder Null, wenn der angeforderte Listener nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="7e270-107">The next stage of the definition or null if the requested listener does not exist.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithListener.WithoutListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithListener.WithoutListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="7e270-108">Der Name des Listeners zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="7e270-108">The name of the listener to remove.</span></span></param>
        <summary>
            <span data-ttu-id="7e270-109">Entfernt einen Front-End-Listener aus das Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="7e270-109">Removes a frontend listener from the application gateway.</span></span>
            <span data-ttu-id="7e270-110">Beachten Sie, dass das Entfernen eines Listeners verwiesen wird, indem Sie andere Einstellungen das Anwendungsgateway umgebrochen werden kann.</span><span class="sxs-lookup"><span data-stu-id="7e270-110">Note that removing a listener referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7e270-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="7e270-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>