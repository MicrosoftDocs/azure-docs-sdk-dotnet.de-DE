<Type Name="IWithStandardCreate" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate">
  <TypeSignature Language="C#" Value="public interface IWithStandardCreate : Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate, Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreateBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStandardCreate implements class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate, class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreateBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStandardCreate&#xA;Implements IBeta, ICreatable(Of ICdnProfile), IDefinitionWithTags(Of IWithCreate), IWithCreate, IWithStandardCreateBeta" />
  <TypeSignature Language="F#" Value="type IWithStandardCreate = interface&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;ICdnProfile&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithStandardCreateBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreateBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="72255-101">Die Phase der Definition die enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden, aber auch für andere optionalen Einstellungen angegeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="72255-101">The stage of the definition which contains all the minimum required inputs for the resource to be created but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate&gt; DefineNewEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate&gt; DefineNewEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate.DefineNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewEndpoint (name As String) As IStandardEndpoint(Of IWithStandardCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate&gt;" Usage="iWithStandardCreate.DefineNewEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="72255-102">Ein neuer Endpunktname.</span><span class="sxs-lookup"><span data-stu-id="72255-102">A new endpoint name.</span></span></param>
        <summary>
            <span data-ttu-id="72255-103">Startet die Definition eines neuen Endpunkts an das CDN-Profil angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="72255-103">Starts the definition of a new endpoint to be attached to the CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="72255-104">Die erste Phase der Definition eines neuen CDN-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="72255-104">The first stage of a new CDN endpoint definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate WithNewEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate WithNewEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate.WithNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewEndpoint (endpointOriginHostname As String) As IWithStandardCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate" Usage="iWithStandardCreate.WithNewEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Definition.IWithStandardCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname"><span data-ttu-id="72255-105">ein Endpunkt Hostname des Ursprungs.</span><span class="sxs-lookup"><span data-stu-id="72255-105">An endpoint origin hostname.</span></span></param>
        <summary>
            <span data-ttu-id="72255-106">Der CDN-Profil hinzugefügt neuen Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="72255-106">Adds new endpoint to the CDN profile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="72255-107">die nächste Phase der Definition der CDN-Profil.</span><span class="sxs-lookup"><span data-stu-id="72255-107">The next stage of CDN profile definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>