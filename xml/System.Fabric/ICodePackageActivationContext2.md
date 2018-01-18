<Type Name="ICodePackageActivationContext2" FullName="System.Fabric.ICodePackageActivationContext2">
  <TypeSignature Language="C#" Value="public interface ICodePackageActivationContext2 : IDisposable, System.Fabric.ICodePackageActivationContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICodePackageActivationContext2 implements class System.Fabric.ICodePackageActivationContext, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ICodePackageActivationContext2" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICodePackageActivationContext2&#xA;Implements ICodePackageActivationContext, IDisposable" />
  <TypeSignature Language="F#" Value="type ICodePackageActivationContext2 = interface&#xA;    interface ICodePackageActivationContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.ICodePackageActivationContext</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="5c500-101">Stellt Aktivierungskontext für die Fabric-Dienst aktiviert Service.</span><span class="sxs-lookup"><span data-stu-id="5c500-101">Represents activation context for the Service Fabric activated service.</span></span>
            </summary>
    <remarks><span data-ttu-id="5c500-102">Enthält Informationen über das Dienstmanifest sowie Informationen zu dem Paket derzeit aktivierten Code Geschäfts-Directory, die Kontext-Id usw.</span><span class="sxs-lookup"><span data-stu-id="5c500-102">Includes information from the service manifest as well as information about the currently activated code package like work directory, context id etc.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName="ServiceListenAddress">
      <MemberSignature Language="C#" Value="public string ServiceListenAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext2.ServiceListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServiceListenAddress : string" Usage="System.Fabric.ICodePackageActivationContext2.ServiceListenAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5c500-103">Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c500-103">The address at which the service should start the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5c500-104">Die Adresse, an der den Listener für die Kommunikation der Dienst gestartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5c500-104">The address at which the service should start the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePublishAddress">
      <MemberSignature Language="C#" Value="public string ServicePublishAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ICodePackageActivationContext2.ServicePublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ServicePublishAddress : string" Usage="System.Fabric.ICodePackageActivationContext2.ServicePublishAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="5c500-105">Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</span><span class="sxs-lookup"><span data-stu-id="5c500-105">The address which the service should publish as the listen address.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="5c500-106">Die Adresse, die der Dienst als die abhöradresse veröffentlichen.</span><span class="sxs-lookup"><span data-stu-id="5c500-106">The address which the service should publish as the listen address.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>