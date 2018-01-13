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
            Die Phase der Definition die enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden, aber auch für andere optionalen Einstellungen angegeben werden kann.
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
        <param name="name">Ein neuer Endpunktname.</param>
        <summary>
            Startet die Definition eines neuen Endpunkts an das CDN-Profil angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition eines neuen CDN-Endpunkt.</return>
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
        <param name="endpointOriginHostname">ein Endpunkt Hostname des Ursprungs.</param>
        <summary>
            Der CDN-Profil hinzugefügt neuen Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition der CDN-Profil.</return>
      </Docs>
    </Member>
  </Members>
</Type>