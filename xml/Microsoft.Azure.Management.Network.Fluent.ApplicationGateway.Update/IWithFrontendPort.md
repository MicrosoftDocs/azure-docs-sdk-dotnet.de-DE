<Type Name="IWithFrontendPort" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="63f28-101">Die Phase von einer Anwendung Gateway Update ermöglicht Front-End-Ports ändern.</span><span class="sxs-lookup"><span data-stu-id="63f28-101">The stage of an application gateway update allowing to modify frontend ports.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="63f28-102">eine Portnummer an.</span><span class="sxs-lookup"><span data-stu-id="63f28-102">A port number.</span></span></param>
        <summary>
            <span data-ttu-id="63f28-103">Erstellt einen Front-End-Port mit einem automatisch generierten Namen und die angegebene Portnummer an, sofern diese nicht bereits eine vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="63f28-103">Creates a frontend port with an auto-generated name and the specified port number, unless one already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="63f28-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="63f28-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort (int portNumber, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithFrontendPort(int32 portNumber, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithFrontendPort(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFrontendPort (portNumber As Integer, name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFrontendPort : int * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithFrontendPort (portNumber, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="63f28-105">eine Portnummer an.</span><span class="sxs-lookup"><span data-stu-id="63f28-105">A port number.</span></span></param>
        <param name="name"><span data-ttu-id="63f28-106">Der Name der Port zuweisen.</span><span class="sxs-lookup"><span data-stu-id="63f28-106">The name to assign to the port.</span></span></param>
        <summary>
            <span data-ttu-id="63f28-107">Erstellt einen Front-End-Port mit dem angegebenen Namen und die Portnummer an, sofern diese kein Port, der Abgleich dieser Namen und/oder Anzahl bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="63f28-107">Creates a frontend port with the specified name and port number, unless a port matching this name and/or number already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="63f28-108">die nächste Phase der Definition oder Null, wenn Sie einen Abgleich der Name oder die Anzahl jedoch nicht zu beiden Port ist bereits vorhanden.</span><span class="sxs-lookup"><span data-stu-id="63f28-108">The next stage of the definition, or null if a port matching either the name or the number, but not both, already exists.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (portNumber As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="63f28-109">Die Nummer des Ports des Front-End-Ports zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="63f28-109">The port number of the frontend port to remove.</span></span></param>
        <summary>
            <span data-ttu-id="63f28-110">Entfernt den angegebenen Front-End-Port an.</span><span class="sxs-lookup"><span data-stu-id="63f28-110">Removes the specified frontend port.</span></span>
            <span data-ttu-id="63f28-111">Beachten Sie, dass entfernen einen Front-End-Port andere Einstellungen verweist das Anwendungsgateway unterbrechen kann.</span><span class="sxs-lookup"><span data-stu-id="63f28-111">Note that removing a frontend port referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="63f28-112">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="63f28-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontendPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontendPort(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontendPort.WithoutFrontendPort(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontendPort (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontendPort : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontendPort.WithoutFrontendPort name" />
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
        <param name="name"><span data-ttu-id="63f28-113">Der Name des Front-End-Ports zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="63f28-113">The name of the frontend port to remove.</span></span></param>
        <summary>
            <span data-ttu-id="63f28-114">Entfernt den angegebenen Front-End-Port an.</span><span class="sxs-lookup"><span data-stu-id="63f28-114">Removes the specified frontend port.</span></span>
            <span data-ttu-id="63f28-115">Beachten Sie, dass entfernen einen Front-End-Port andere Einstellungen verweist das Anwendungsgateway unterbrechen kann.</span><span class="sxs-lookup"><span data-stu-id="63f28-115">Note that removing a frontend port referenced by other settings may break the application gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="63f28-116">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="63f28-116">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>