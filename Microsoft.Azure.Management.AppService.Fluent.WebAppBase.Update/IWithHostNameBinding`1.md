<Type Name="IWithHostNameBinding&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameBinding&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameBinding`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostNameBinding(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithHostNameBinding&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT">Der Typ der Ressource.</typeparam>
    <summary>
            Die Phase der Web-app aktualisieren, sodass Hostnamen-Bindungen festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt; DefineHostnameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt;&gt; DefineHostnameBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.DefineHostnameBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineHostnameBinding () As IBlank(Of IUpdate(Of FluentT))" />
      <MemberSignature Language="F#" Value="abstract member DefineHostnameBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;&gt;" Usage="iWithHostNameBinding.DefineHostnameBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die Definition einen neuen Hostnamen-Bindungen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase eines Hostnamens Bindung Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedHostnameBindings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithManagedHostnameBindings (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithManagedHostnameBindings(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithManagedHostnameBindings(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithManagedHostnameBindings (domain As IAppServiceDomain, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedHostnameBindings : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithManagedHostnameBindings (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain">Der Azure verwaltete Domäne.</param>
        <param name="hostnames">Die Liste der untergeordneten Domänen.</param>
        <summary>
            Definiert eine Liste von Hostnamen für eine Azure verwalteten Domäne konfigurieren. Der DNS-Eintragstyp wird standardmäßig für CNAME mit Ausnahme der Servicelevel-Stammdomäne sein (".
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung der Web-app.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutHostnameBinding (string hostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutHostnameBinding(string hostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithoutHostnameBinding(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutHostnameBinding (hostname As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutHostnameBinding : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithoutHostnameBinding hostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostname">Der Hostname zum Aufheben der Bindung.</param>
        <summary>
            Hebt die Bindung eines Hostnamens aus der Web-app.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung der Web-app.</return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyHostnameBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithThirdPartyHostnameBinding (string domain, params string[] hostnames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithThirdPartyHostnameBinding(string domain, string[] hostnames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithHostNameBinding`1.WithThirdPartyHostnameBinding(System.String,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyHostnameBinding (domain As String, ParamArray hostnames As String()) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyHostnameBinding : string * string[] -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithHostNameBinding.WithThirdPartyHostnameBinding (domain, hostnames)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="System.String" />
        <Parameter Name="hostnames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="domain">Der Name der externen Domäne.</param>
        <param name="hostnames">Die Liste der untergeordneten Domänen.</param>
        <summary>
            Definiert eine Liste von Hostnamen einer extern erworbener App-Domäne. Die Hostnamen müssen vor der Hand, zeigen Sie auf die Web-app konfiguriert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung der Web-app.</return>
      </Docs>
    </Member>
  </Members>
</Type>