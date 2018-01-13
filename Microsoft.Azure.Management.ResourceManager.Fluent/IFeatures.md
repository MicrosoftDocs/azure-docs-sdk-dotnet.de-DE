<Type Name="IFeatures" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures">
  <TypeSignature Language="C#" Value="public interface IFeatures : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFeatures implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFeatures&#xA;Implements ISupportsListing(Of IFeature)" />
  <TypeSignature Language="F#" Value="type IFeatures = interface&#xA;    interface ISupportsListing&lt;IFeature&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Einstiegspunkt für einen Funktionen Verwaltungs-API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.IFeature Register (string resourceProviderNamespace, string featureName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature Register(string resourceProviderNamespace, string featureName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures.Register(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Register (resourceProviderNamespace As String, featureName As String) As IFeature" />
      <MemberSignature Language="F#" Value="abstract member Register : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Fluent.IFeature" Usage="iFeatures.Register (resourceProviderNamespace, featureName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.IFeature</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace">der Namespace des Ressourcenanbieters</param>
        <param name="featureName">der Name der Funktion</param>
        <summary>
            Registriert eine Funktion in einem Ressourcenanbieter an.
            </summary>
        <returns>Das erstellte unveränderlichen clientseitige Funktion-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt; RegisterAsync (string resourceProviderNamespace, string featureName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt; RegisterAsync(string resourceProviderNamespace, string featureName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IFeatures.RegisterAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;" Usage="iFeatures.RegisterAsync (resourceProviderNamespace, featureName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IFeature&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="featureName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceProviderNamespace">der Namespace des Ressourcenanbieters</param>
        <param name="featureName">FeatureName den Namen der Funktion</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Registriert eine Funktion in einem Ressourcenanbieter an.
            </summary>
        <returns>Das erstellte unveränderlichen clientseitige Funktion-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>