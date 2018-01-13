<Type Name="IAppServiceCertificateOrder" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder">
  <TypeSignature Language="C#" Value="public interface IAppServiceCertificateOrder : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceCertificateOrder implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceCertificateOrder&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, AppServiceCertificateOrderInner), IHasInner(Of AppServiceCertificateOrderInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServiceCertificateOrder), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAppServiceCertificateOrder = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, AppServiceCertificateOrderInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;AppServiceCertificateOrderInner&gt;&#xA;    interface IRefreshable&lt;IAppServiceCertificateOrder&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServiceCertificateOrderInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung einer Bestellung eine Azure App Service-Zertifikat.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public bool AutoRenew { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoRenew As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, wenn das Zertifikat beim Ablauf automatisch erneuert werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateSigningRequest">
      <MemberSignature Language="C#" Value="public string CertificateSigningRequest { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateSigningRequest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CertificateSigningRequest" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateSigningRequest As String" />
      <MemberSignature Language="F#" Value="member this.CertificateSigningRequest : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CertificateSigningRequest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft letzten Anforderung Signieren des Zertifikats, das für diesen Auftrag erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyVaultBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding CreateKeyVaultBinding (string certificateName, Microsoft.Azure.Management.KeyVault.Fluent.IVault vault);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding CreateKeyVaultBinding(string certificateName, class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CreateKeyVaultBinding(System.String,Microsoft.Azure.Management.KeyVault.Fluent.IVault)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateKeyVaultBinding (certificateName As String, vault As IVault) As IAppServiceCertificateKeyVaultBinding" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyVaultBinding : string * Microsoft.Azure.Management.KeyVault.Fluent.IVault -&gt; Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding" Usage="iAppServiceCertificateOrder.CreateKeyVaultBinding (certificateName, vault)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
      </Parameters>
      <Docs>
        <param name="certificateName">Der Name des geheimen Schlüssels Tresor.</param>
        <param name="vault">Der schlüsseltresor des Zertifikats.</param>
        <summary>
            Binden Sie ein Key Vault Geheimnis in einen Zertifikatspeicher, der verwendet wird, für das Speichern des Zertifikats, sobald er bereit ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine Bindung, die den schlüsseltresor-Informationen enthält.</return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyVaultBindingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; CreateKeyVaultBindingAsync (string certificateName, Microsoft.Azure.Management.KeyVault.Fluent.IVault vault, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; CreateKeyVaultBindingAsync(string certificateName, class Microsoft.Azure.Management.KeyVault.Fluent.IVault vault, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.CreateKeyVaultBindingAsync(System.String,Microsoft.Azure.Management.KeyVault.Fluent.IVault,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyVaultBindingAsync : string * Microsoft.Azure.Management.KeyVault.Fluent.IVault * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;" Usage="iAppServiceCertificateOrder.CreateKeyVaultBindingAsync (certificateName, vault, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="vault" Type="Microsoft.Azure.Management.KeyVault.Fluent.IVault" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateName">Der Name des geheimen Schlüssels Tresor.</param>
        <param name="vault">Der schlüsseltresor des Zertifikats.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Binden Sie ein Key Vault Geheimnis in einen Zertifikatspeicher, der verwendet wird, für das Speichern des Zertifikats, sobald er bereit ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine Bindung, die den schlüsseltresor-Informationen enthält.</return>
      </Docs>
    </Member>
    <Member MemberName="DistinguishedName">
      <MemberSignature Language="C#" Value="public string DistinguishedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DistinguishedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DistinguishedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DistinguishedName As String" />
      <MemberSignature Language="F#" Value="member this.DistinguishedName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DistinguishedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die distinguished Name des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainVerificationToken">
      <MemberSignature Language="C#" Value="public string DomainVerificationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainVerificationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DomainVerificationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DomainVerificationToken As String" />
      <MemberSignature Language="F#" Value="member this.DomainVerificationToken : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.DomainVerificationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Überprüfung der Domäne ab, das token.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ablaufzeit.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVaultBinding">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding GetKeyVaultBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding GetKeyVaultBinding() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.GetKeyVaultBinding" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeyVaultBinding () As IAppServiceCertificateKeyVaultBinding" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVaultBinding : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding" Usage="iAppServiceCertificateOrder.GetKeyVaultBinding " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Der Status des geheimen Schlüssels Key Vault.</return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVaultBindingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; GetKeyVaultBindingAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt; GetKeyVaultBindingAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.GetKeyVaultBindingAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVaultBindingAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;" Usage="iAppServiceCertificateOrder.GetKeyVaultBindingAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateKeyVaultBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Der Status des geheimen Schlüssels Key Vault.</return>
      </Docs>
    </Member>
    <Member MemberName="Intermediate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Intermediate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Intermediate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Intermediate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Intermediate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Intermediate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Zwischenzertifikat ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySize">
      <MemberSignature Language="C#" Value="public int KeySize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 KeySize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.KeySize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeySize As Integer" />
      <MemberSignature Language="F#" Value="member this.KeySize : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.KeySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zertifikatschlüsselgröße ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCertificateIssuanceTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastCertificateIssuanceTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastCertificateIssuanceTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.LastCertificateIssuanceTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCertificateIssuanceTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastCertificateIssuanceTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.LastCertificateIssuanceTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die zuletzt Ausstellung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProductType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType ProductType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType ProductType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ProductType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProductType As CertificateProductType" />
      <MemberSignature Language="F#" Value="member this.ProductType : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ProductType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateProductType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ für das Produkt ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Root">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails Root" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Root" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Root As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.Root : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Root" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Stammzertifizierungsstellen-Zertifikat ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerialNumber">
      <MemberSignature Language="C#" Value="public string SerialNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SerialNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SerialNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerialNumber As String" />
      <MemberSignature Language="F#" Value="member this.SerialNumber : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SerialNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die aktuellen Seriennummer des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignedCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails SignedCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SignedCertificate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SignedCertificate As CertificateDetails" />
      <MemberSignature Language="F#" Value="member this.SignedCertificate : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.SignedCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft dem signierten Zertifikat ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As CertificateOrderStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CertificateOrderStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die aktuellen Auftragsstatus ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidityInYears">
      <MemberSignature Language="C#" Value="public int ValidityInYears { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ValidityInYears" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ValidityInYears" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidityInYears As Integer" />
      <MemberSignature Language="F#" Value="member this.ValidityInYears : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.ValidityInYears" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Dauer der einzelnen Jahre (muss zwischen 1 und 3 liegen).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.VerifyDomainOwnership(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (domain As IAppServiceDomain)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain -&gt; unit" Usage="iAppServiceCertificateOrder.VerifyDomainOwnership domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
      </Parameters>
      <Docs>
        <param name="domain">Der Azure verwaltete Domäne.</param>
        <summary>
            Überprüft den Besitz der Domäne durch die Bereitstellung von Azure erworben Domäne.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder.VerifyDomainOwnershipAsync(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAppServiceCertificateOrder.VerifyDomainOwnershipAsync (domain, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="domain">Der Azure verwaltete Domäne.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Überprüft den Besitz der Domäne durch die Bereitstellung von Azure erworben Domäne.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Observable-Objekt, das Ergebnis.</return>
      </Docs>
    </Member>
  </Members>
</Type>