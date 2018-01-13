<Type Name="NamespaceManager" FullName="Microsoft.ServiceBus.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt eine Premium-Klasse, die bei der Verwaltung von Entitäten, z. B. Warteschlangen, Themen, Abonnements und Regeln in Ihren Dienstnamespace dar. Sie müssen Dienstnamespace Adresse und den Zugriff Anmeldeinformationen angeben, um Ihren Dienstnamespace zu verwalten.</summary>
    <remarks>To be added.</remarks>
    <example>
      <code>
             NamespaceManagerSettings NsSettings = neue NamespaceManagerSettings(); mit den Anmeldeinformationen und Vorgang Timeout NamespaceManager-Manager neue NamespaceManager = (neue Uri("baseUri"), NsSettings);
             </code>
    </example>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit den angegebenen Adressen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit den angegebenen Dienst Namespace-URI-Basisadressen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace Dienstadresse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse. </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Einstellungen.</summary>
        <remarks>Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist kein, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adressen Itse sein muss LF.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;string&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Anbieter von Sicherheitstoken.</summary>
        <remarks>Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Einstellungen.</summary>
        <remarks>Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : seq&lt;Uri&gt; * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Anbieter von Sicherheitstoken.</summary>
        <remarks>Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt.</summary>
        <remarks>Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="settings" /> ist NULL.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.String,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : string * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und Anbieter von Sicherheitstoken.</summary>
        <remarks>Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="tokenProvider" /> ist NULL.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.NamespaceManagerSettings -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.ServiceBus.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> und <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt.</summary>
        <remarks>Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="settings" /> ist NULL.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.ServiceBus.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.ServiceBus.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.#ctor(System.Uri,Microsoft.ServiceBus.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.NamespaceManager : Uri * Microsoft.ServiceBus.TokenProvider -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="new Microsoft.ServiceBus.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.ServiceBus.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <param name="tokenProvider">Das Sicherheitsobjekt Tokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.ServiceBus.TokenProvider" /> Objekt.</summary>
        <remarks>Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="tokenProvider" /> ist NULL.</exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.ServiceBus.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Basisadresse des Diensts-Namespace ab.</summary>
        <value>Ein <see cref="T:System.Uri" /> , der die Basisadresse des Diensts Namespace darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</summary>
        <returns>Eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</param>
        <summary>Erstellt eine Event Hubs-Consumer-Gruppe unter Verwendung des angegebenen <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer".</param>
        <summary>Erstellt eine Event Hubs-Consumer-Gruppe mit Default-Werten, mit der angegebenen Event Hubs-Pfad und einen Namen für die consumergruppe.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer".</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroup(System.String,System.String)" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />-Objekt.</param>
        <summary>Eine consumergruppe erstellt, wenn er nicht bereits unter Verwendung des angegebenen vorhanden ist, <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> als Metadaten. Wenn die Gruppe bereits vorhanden ist, klicken Sie dann zurück gespeicherten <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</summary>
        <returns>Gibt zurück, die neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />. Wenn die consumergruppe bereits vorhanden ist, gibt die vorhandene <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription CreateConsumerGroupIfNotExists(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExists (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExists : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.CreateConsumerGroupIfNotExists (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer" zu erstellen.</param>
        <summary>Erstellt eine consumergruppe, wenn er nicht bereits mit dem angegebenen Namen von Event Hubs Pfad und der Gruppe vorhanden ist. Wenn die Gruppe bereits vorhanden ist, klicken Sie dann zurück gespeicherten <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</summary>
        <returns>Gibt zurück, die neu erstellte <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />. Wenn die consumergruppe bereits vorhanden ist, gibt die vorhandene <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die Beschreibung für den Consumer-Gruppe.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateConsumerGroupIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; CreateConsumerGroupIfNotExistsAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateConsumerGroupIfNotExistsAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateConsumerGroupIfNotExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.CreateConsumerGroupIfNotExistsAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer".</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.CreateConsumerGroupIfNotExists(System.String,System.String)" />.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</param>
        <summary>Erstellt einen neuen Event Hub mithilfe des angegebenen <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt einen neuen Event Hub mit Standardwerten, für der angegebene Eingabepfad an.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das den Event Hub erstellen beschreibt.</param>
        <summary>Erstellt asynchron einen Event Hub.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt asynchron einen Event Hub.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das den Event Hub erstellen beschreibt.</param>
        <summary>Erstellt einen Event Hub an, wenn er nicht vorhanden ist.</summary>
        <returns>Gibt ein<see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExists">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription CreateEventHubIfNotExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExists (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExists : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.CreateEventHubIfNotExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Erstellt einen Event Hub an, wenn er nicht vorhanden ist.</summary>
        <returns>Gibt ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Der Hub-Beschreibung des Ereignisses.</param>
        <summary>Erstellt einen Event Hub asynchron, wenn er nicht vorhanden ist.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEventHubIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; CreateEventHubIfNotExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateEventHubIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateEventHubIfNotExistsAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateEventHubIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.CreateEventHubIfNotExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Event Hubs.</param>
        <summary>Erstellt einen Event Hub asynchron, wenn er nicht vorhanden ist.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang abschließt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindung unkompliziert verwendet.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> mithilfe der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Eine neue Instanz von <see cref="T:Microsoft.ServiceBus.NamespaceManager" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt die Attribute, mit denen die neue Warteschlange erstellt werden.</param>
        <summary>Erstellt eine neue Warteschlange im Dienstnamespace mit der angegebenen warteschlangenbeschreibung an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription CreateQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.CreateQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.CreateQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt eine neue Warteschlange im Dienstnamespace mit dem angegebenen Pfad.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Die Länge des <paramref name="path" /> 290 Zeichen übersteigt.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Unter desselben Namespace befindet sich eine Warteschlange oder ein Thema mit dem gleichen Namen und Pfad.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException">Die angegebene Größe in der Beschreibung wird nicht unterstützt oder die maximale zulässige Kontingent erreicht haben. Sie müssen Geben Sie einen der unterstützten Größenwerte, löschen vorhandene Entitäten oder Ihr Kontingent vergrößern.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Der Server wird mit logischen Operationen überladen. Sie können erwägen Sie keines der folgenden Aktionen: Warten Sie, und wiederholen Sie das Aufrufen dieser Funktion. Entfernen von Entitäten vor Wiederholung (z. B. Empfangen von Nachrichten vor dem Senden keine weiteren).</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt die Attribute, mit denen die neue Warteschlange erstellt werden.</param>
        <summary>Erstellt asynchron eine neue Warteschlange im Dienstnamespace mit der angegebenen warteschlangenbeschreibung ein.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; CreateQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.CreateQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt asynchron eine neue Warteschlange im Dienstnamespace mit dem angegebenen Pfad.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> der neu erstellten Warteschlange.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen das neue Relay erstellt wird.</param>
        <summary>Erstellt ein neues Relay im Dienstnamespace mit dem angegebenen Relay-Beschreibung an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription CreateRelay(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelay(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelay (path As String, type As RelayType) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.CreateRelay : string * Microsoft.ServiceBus.RelayType -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.CreateRelay (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="type">Der Relay-Typ.</param>
        <summary>Erstellt ein neues Relay im Dienstnamespace mit dem angegebenen Pfad und den Typ an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen das neue Relay erstellt wird.</param>
        <summary>Erstellt asynchron ein neues Relay im Dienstnamespace mit dem angegebenen Relay-Beschreibung an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync (string path, Microsoft.ServiceBus.RelayType type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; CreateRelayAsync(string path, valuetype Microsoft.ServiceBus.RelayType type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateRelayAsync(System.String,Microsoft.ServiceBus.RelayType)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateRelayAsync (path As String, type As RelayType) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateRelayAsync : string * Microsoft.ServiceBus.RelayType -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.CreateRelayAsync (path, type)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.ServiceBus.RelayType" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="type">Der Relay-Typ.</param>
        <summary>Erstellt asynchron ein neues Relay im Dienstnamespace mit dem angegebenen Pfad und den Typ an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> Objekt für das neu erstellte Relay.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit der Beschreibung angegebenen Abonnement.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Standardmäßig wird ein Filter "Pass-Through" für dieses Abonnement erstellt dies, dass er alle Nachrichten bedeutet zu diesem Abonnement gesendet werden kann. Der Name des Filters ist <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <param name="filter">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und den Filterausdruck an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Eine Standardregel erstellt, die mit Daten aus <paramref name="filter" /> und als benannte <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />. </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <param name="ruleDescription">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und die Regelbeschreibung an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Eine Standardregel erstellt, die mit Daten aus <paramref name="ruleDescription" />.
            Wenn <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> ist Null oder ein Leerzeichen, und klicken Sie dann der Namen der Regel erstellt werden <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />. </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen Thema Pfad und Abonnement an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Standardmäßig wird ein Filter "Pass-Through" für dieses Abonnement erstellt dies, dass er alle Nachrichten bedeutet zu diesem Abonnement gesendet werden kann. Der Name des Filters ist <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="filter">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit dem angegebenen themenpfad, den Abonnementnamen und den Filterausdruck an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Eine Standardregel erstellt, die mit Daten aus <paramref name="filter" /> und als benannte <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />. </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription CreateSubscription(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscription(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscription : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.CreateSubscription (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="ruleDescription">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</param>
        <summary>Erstellt ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Regelbeschreibung an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des neu erstellten Abonnements.</returns>
        <remarks> Eine Standardregel erstellt, die mit Daten aus <paramref name="ruleDescription" />.
            Wenn <see cref="P:Microsoft.ServiceBus.Messaging.RuleDescription.Name" /> ist Null oder ein Leerzeichen, und klicken Sie dann der Namen der Regel erstellt werden <see cref="F:Microsoft.ServiceBus.Messaging.RuleDescription.DefaultRuleName" />. </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der Beschreibung angegebenen Abonnement.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <param name="filter">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und den Filterausdruck an.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (description, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Abonnement erstellt werden.</param>
        <param name="ruleDescription">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen abonnementbeschreibung und die Regelbeschreibung ein.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit dem angegebenen Thema Pfad und Abonnement an.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.Filter filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.Filter filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.Filter)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.Filter -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="filter" Type="Microsoft.ServiceBus.Messaging.Filter" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="filter">Der Filterausdruck, der zur Erfassung von Nachrichten, die den Filterwert Ausdruck erfüllen.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Filter-Ausdruck ein.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync (string topicPath, string name, Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; CreateSubscriptionAsync(string topicPath, string name, class Microsoft.ServiceBus.Messaging.RuleDescription ruleDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateSubscriptionAsync(System.String,System.String,Microsoft.ServiceBus.Messaging.RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateSubscriptionAsync : string * string * Microsoft.ServiceBus.Messaging.RuleDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.CreateSubscriptionAsync (topicPath, name, ruleDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ruleDescription" Type="Microsoft.ServiceBus.Messaging.RuleDescription" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <param name="ruleDescription">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RuleDescription" /> -Objekt, das die Attribute, die Nachrichten werden mit dem abgeglichen und Reaktionen bewirkten, beschreibt.</param>
        <summary>Erstellt asynchron ein neues Abonnement im Dienstnamespace mit der angegebenen themenpfad, Abonnementnamen und Regelbeschreibung ein.</summary>
        <returns>Die asynchron erstellte Abonnement.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Thema erstellt werden.</param>
        <summary>Erstellt ein neues Thema innerhalb des Dienstnamespace mit der Beschreibung angegebene Thema an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des neu erstellten Themas.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription CreateTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.CreateTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.CreateTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt ein neues Thema innerhalb des Dienstnamespace mit den angegebenen Namespace Dienstpfad an.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des neu erstellten Themas.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist null oder leer ist, oder <paramref name="path" /> beginnt oder endet mit "/".</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Länge des <paramref name="path" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Unter desselben Namespace befindet sich eine Warteschlange oder ein Thema mit dem gleichen Namen und Pfad.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.QuotaExceededException">Die angegebene Größe in der Beschreibung wird nicht unterstützt oder die maximale zulässige Kontingent erreicht haben. Sie müssen Geben Sie einen der unterstützten Größenwerte, löschen vorhandene Entitäten oder Ihr Kontingent vergrößern.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, beschreibt die Attribute, mit denen das neue Thema erstellt werden.</param>
        <summary>Erstellt asynchron in den Dienstnamespace ein neues Thema mit der Beschreibung angegebene Thema ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; CreateTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.CreateTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.CreateTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Erstellt asynchron in den Dienstnamespace ein neues Thema mit den angegebenen Namespace Dienstpfad an.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroup">
      <MemberSignature Language="C#" Value="public void DeleteConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteConsumerGroup (eventHubPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroup : string * string -&gt; unit" Usage="namespaceManager.DeleteConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name des zu löschenden consumergruppe.</param>
        <summary>Löscht eine consumergruppe.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteConsumerGroupAsync (eventHubPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name des zu löschenden consumergruppe.</param>
        <summary>Löscht asynchron eine consumergruppe.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHub">
      <MemberSignature Language="C#" Value="public void DeleteEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteEventHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHub : string -&gt; unit" Usage="namespaceManager.DeleteEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Löscht einen Event Hub.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteEventHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteEventHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Löscht asynchron einen Event Hub.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueue">
      <MemberSignature Language="C#" Value="public void DeleteQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteQueue (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteQueue : string -&gt; unit" Usage="namespaceManager.DeleteQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht die Warteschlange, die durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist leer oder null, oder <paramref name="path" /> beginnt oder endet mit "/".</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Die Länge des <paramref name="path" /> ist größer als <see cref="F:Microsoft.ServiceBus.Messaging.Constants.QueueNameMaximumLength" />.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Warteschlange ist unter diesem Pfad nicht vorhanden.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteQueueAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteQueueAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht asynchron die Warteschlange, die durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <returns>Der asynchrone Warteschlangenvorgang zum Löschen der.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelay">
      <MemberSignature Language="C#" Value="public void DeleteRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteRelay (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteRelay : string -&gt; unit" Usage="namespaceManager.DeleteRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht das Relay durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteRelayAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteRelayAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht asynchron das Relay durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <returns>Der asynchrone Löschvorgang Relay.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscription">
      <MemberSignature Language="C#" Value="public void DeleteSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteSubscription (topicPath As String, name As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscription : string * string -&gt; unit" Usage="namespaceManager.DeleteSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements zu löschen.</param>
        <summary>Löscht das Abonnement mit dem angegebenen Pfad und Abonnement Themanamen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteSubscriptionAsync (topicPath As String, name As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements zu löschen.</param>
        <summary>Löscht asynchron das Abonnement mit dem angegebenen Pfad und Abonnement Themanamen.</summary>
        <returns>Der asynchrone Abonnementvorgang zum Löschen der.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopic">
      <MemberSignature Language="C#" Value="public void DeleteTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteTopic (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteTopic : string -&gt; unit" Usage="namespaceManager.DeleteTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht das Thema, das durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist null oder leer ist, oder <paramref name="path" /> beginnt oder endet mit "/".</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.DeleteTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteTopicAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteTopicAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Löscht asynchron das Thema, das durch den Pfad relativ zur Basisadresse Diensts-Namespace beschrieben.</summary>
        <returns>Der Vorgang des asynchronen gelöschtes Thema.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExists">
      <MemberSignature Language="C#" Value="public bool EventHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool EventHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.EventHubExists : string -&gt; bool" Usage="namespaceManager.EventHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Gibt an, und zwar unabhängig davon, ob ein Event Hub vorhanden ist.</summary>
        <returns>Gibt "true" zurück, wenn der Event Hub vorhanden ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; EventHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; EventHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.EventHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function EventHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EventHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.EventHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Event Hubs.</param>
        <summary>Ermittelt asynchron, ob der Event Hub aus dem Dienstnamespace vorhanden ist. </summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription GetConsumerGroup(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroup (eventHubPath As String, name As String) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroup : string * string -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.GetConsumerGroup (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer".</param>
        <summary>Ruft ein Event Hubs-Consumer-Gruppe ab.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroupAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupAsync (eventHubPath As String, name As String) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroupAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Der Name der Gruppe "Consumer".</param>
        <summary>Ruft asynchron eine consumergruppe ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; GetConsumerGroups(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroups(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroups (eventHubPath As String) As IEnumerable(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroups : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.GetConsumerGroups eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <summary>Ruft eine Auflistung, die einen Satz von consumergruppen darstellt.</summary>
        <returns>Gibt ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> Objekt, das den Satz von consumergruppen darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConsumerGroupsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync (string eventHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt; GetConsumerGroupsAsync(string eventHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetConsumerGroupsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConsumerGroupsAsync (eventHubPath As String) As Task(Of IEnumerable(Of ConsumerGroupDescription))" />
      <MemberSignature Language="F#" Value="member this.GetConsumerGroupsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;" Usage="namespaceManager.GetConsumerGroupsAsync eventHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <summary>Ruft asynchron einen Satz von consumergruppen ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription GetEventHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHub (path As String) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHub : string -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.GetEventHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Ruft Informationen zu einem Event Hub ab.</summary>
        <returns>Gibt ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das die Event Hub-Beschreibung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubAsync (path As String) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu den Event Hub.</param>
        <summary>Ruft die Informationen zu einem Event Hub asynchron ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Die ID der Event Hub-Partition.</param>
        <summary>Gibt Informationen über die angegebene Event Hub-Partition zurück. Diese Methode setzt voraus, sollen von Partitionsinformationen für die Partition, die gemäß der <paramref name="name" /> Parameter, der die standardconsumergruppe gehört verweist <paramref name="eventHubPath" />.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.PartitionDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartition">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.PartitionDescription GetEventHubPartition(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartition (eventHubPath As String, consumerGroupName As String, name As String) As PartitionDescription" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartition : string * string * string -&gt; Microsoft.ServiceBus.Messaging.PartitionDescription" Usage="namespaceManager.GetEventHubPartition (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.PartitionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath"></param>
        <param name="consumerGroupName"></param>
        <param name="name"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="name">Die ID der Event Hub-Partition.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync (string eventHubPath, string consumerGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.PartitionDescription&gt; GetEventHubPartitionAsync(string eventHubPath, string consumerGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartitionAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubPartitionAsync (eventHubPath As String, consumerGroupName As String, name As String) As Task(Of PartitionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubPartitionAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;" Usage="namespaceManager.GetEventHubPartitionAsync (eventHubPath, consumerGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.PartitionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventHubPath" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="eventHubPath">Der Pfad zu den Event Hub.</param>
        <param name="consumerGroupName">Der Name des Event Hubs-Consumer-Gruppe.</param>
        <param name="name">Die ID der Partition Event Hubs.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubPartition(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; GetEventHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubs () As IEnumerable(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetEventHubs : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.GetEventHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine Auflistung, die einen Satz von Event Hubs darstellt.</summary>
        <returns>Gibt ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> Objekt, das den Satz von Event Hubs darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEventHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt; GetEventHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetEventHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEventHubsAsync () As Task(Of IEnumerable(Of EventHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetEventHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;" Usage="namespaceManager.GetEventHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft asynchron eine Liste von Event Hubs ab.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription GetQueue (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription GetQueue(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueue(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueue (path As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.GetQueue : string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.GetQueue path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft eine Warteschlange aus dem Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> handle für die Warteschlange oder ein <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn die Warteschlange im Dienstnamespace nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist leer oder null, oder <paramref name="path" /> beginnt oder endet mit "/".</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Die Warteschlange ist nicht im Dienstnamespace vorhanden.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueueAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueueAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueueAsync (path As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueueAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueueAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft asynchron eine Warteschlange Dienstnamespace ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues () As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Warteschlangen in der Service-Namespace oder eine leere Auflistung zurück, wenn keine Warteschlange vorhanden ist. </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; GetQueues(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueues(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueues (filter As String) As IEnumerable(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.GetQueues : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.GetQueues filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Eine Zeichenfolge, die zum Filtern der Warteschlangen abgerufen werden sollen.</param>
        <summary>Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace mit dem angegebenen Filter ab. Sie können durch eine Kombination von Entitätsname (einschließlich beginnt mit), Entität Länge (Gt oder Lt), erstellt, aktualisiert und Zugriffs-Zeit (Gt oder Lt) filtern.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Warteschlangen in der Service-Namespace oder eine leere Auflistung zurück, wenn keine Warteschlange vorhanden ist.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var QueuesWithMessages = namespaceManager.GetQueues ("MessageCount Gt 0"); Var QueuesStartsWith = namespaceManager.GetQueues ($"" StartsWith "(Pfad,"Queue") Eq" true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync () As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft asynchron eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueuesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt; GetQueuesAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetQueuesAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetQueuesAsync (filter As String) As Task(Of IEnumerable(Of QueueDescription))" />
      <MemberSignature Language="F#" Value="member this.GetQueuesAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;" Usage="namespaceManager.GetQueuesAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Die Zeichenfolge, die zum Filtern der Warteschlangen abgerufen werden sollen.</param>
        <summary>Asynchron Ruft eine aufzählbare Auflistung von alle Warteschlangen im Dienstnamespace mit angegebenen Filter ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var QueuesWithMessages = "await" namespaceManager.GetQueuesAsync ("MessageCount Gt 0"); Var QueuesStartsWith = "await" namespaceManager.GetQueuesAsync ($"" StartsWith "(Pfad,"Queue") Eq" true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription GetRelay (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription GetRelay(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelay(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelay (path As String) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.GetRelay : string -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.GetRelay path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der relaypfad.</param>
        <summary>Ruft die Details eines bestimmten Relaydienst-Endpunkts ab.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelayAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelayAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelayAsync (path As String) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelayAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelayAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der relaypfad.</param>
        <summary>Ruft Sie die Details eines bestimmten Relaydienst-Endpunkts asynchron ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelays">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; GetRelays() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelays" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelays () As IEnumerable(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRelays : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.GetRelays " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine Auflistung aller Relays im Dienstnamespace ab.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRelaysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt; GetRelaysAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRelaysAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRelaysAsync () As Task(Of IEnumerable(Of RelayDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRelaysAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;" Usage="namespaceManager.GetRelaysAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;GetRelaysAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Eine Auflistung aller Relays im Dienstnamespace asynchron abgerufen.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; GetRevokedPublishers(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishers (entityPath As String) As IEnumerable(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishers : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.GetRevokedPublishers entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Pfad zu den Event Hub. Weitere Informationen finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</param>
        <summary>Gibt alle widerrufenen Verleger in einem Event Hub zurück.</summary>
        <returns>Gibt eine <see cref="T:System.Collections.Generic.IEnumerable`1" /> Auflistung mit den gesperrten Verlegern.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRevokedPublishersAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync (string entityPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt; GetRevokedPublishersAsync(string entityPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishersAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRevokedPublishersAsync (entityPath As String) As Task(Of IEnumerable(Of RevokedPublisherDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRevokedPublishersAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;" Usage="namespaceManager.GetRevokedPublishersAsync entityPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Pfad zu den Event Hub. Weitere Informationen finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.EventHubDescription.Path" />.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.GetRevokedPublishers(System.String)" />.</summary>
        <returns>Gibt eine <see cref="T:System.Threading.Tasks.Task`1" /> , die die gesperrten Verlegern enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <summary>Ruft eine aufzählbare Auflistung aller Regeln im Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Regeln im Dienstnamespace oder eine leere Auflistung zurück, wenn keine Regel vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt; GetRules(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRules(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (topicPath As String, subscriptionName As String, filter As String) As IEnumerable(Of RuleDescription)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string * string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;" Usage="namespaceManager.GetRules (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <param name="filter">Die Zeichenfolge, die zum Filtern der Regeln abgerufen werden sollen.</param>
        <summary>Ruft eine aufzählbare Auflistung aller Regeln im Dienstnamespace mit angegebenen themenpfad, Abonnementnamen und Filter ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, das die Auflistung aller Regeln im Dienstnamespace oder eine leere Auflistung zurück, wenn keine Regel vorhanden ist.</returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a>Filter-Ausdruck-Format: {aus} {logischer Operator} {Value} {Filterausdruck}
            -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Der Wert der entsprechenden Eigenschaftentyp
            </remarks>
        <example>
          <code>
            Var FiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5). ToString ("M/TT/JJJJ hh: mm:"); Var rulesInTheLast5Minutes = namespaceManager.GetRules (Name_des_themas, SubscriptionName "," $"CreatedAt Gt"{FiveMinutesAgo}"");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <summary>Ruft asynchron eine aufzählbare Auflistung aller Regeln im Dienstnamespace ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRulesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync (string topicPath, string subscriptionName, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt; GetRulesAsync(string topicPath, string subscriptionName, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetRulesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRulesAsync (topicPath As String, subscriptionName As String, filter As String) As Task(Of IEnumerable(Of RuleDescription))" />
      <MemberSignature Language="F#" Value="member this.GetRulesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;" Usage="namespaceManager.GetRulesAsync (topicPath, subscriptionName, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.RuleDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Themenname relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="subscriptionName">Der Name des Abonnements.</param>
        <param name="filter">Die Zeichenfolge, die zum Filtern der Regeln abgerufen werden sollen.</param>
        <summary>Ruft asynchron eine aufzählbare Auflistung aller Regeln im Dienstnamespace mit angegebenen themenpfad, Abonnementnamen und Filter ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            <a name="filter-expression-format---propery-logical-operator-value-filter-expression"></a>Filter-Ausdruck-Format: {aus} {logischer Operator} {Value} {Filterausdruck}
            -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Der Wert der entsprechenden Eigenschaftentyp
            </remarks>
        <example>
          <code>
            Var FiveMinutesAgo = DateTime.UtcNow.AddMinutes(-5). ToString ("M/TT/JJJJ hh: mm:"); Var rulesInTheLast5Minutes = "await" namespaceManager.GetRulesAsync (Name_des_themas, SubscriptionName "," $"CreatedAt Gt"{FiveMinutesAgo}"");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription GetSubscription(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscription(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscription (topicPath As String, name As String) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.GetSubscription : string * string -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.GetSubscription (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Ruft das Thema aus dem Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> handle für das Abonnement oder eine <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn das Abonnement nicht im Dienstnamespace vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Das Abonnement ist nicht im Dienstnamespace vorhanden.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptionAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionAsync (topicPath As String, name As String) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptionAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Ruft asynchron Thema Dienstnamespace ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung aller Abonnements im Dienstnamespace oder eine leere Auflistung zurück, wenn kein Abonnement vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; GetSubscriptions(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptions(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptions (topicPath As String, filter As String) As IEnumerable(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptions : string * string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.GetSubscriptions (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="filter">Die Zeichenfolge, die zum Filtern von Abonnements abgerufen werden sollen.</param>
        <summary>Ruft eine aufzählbare Auflistung aller Abonnements im Dienstnamespace angegebenen themenpfad und Filter ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung aller Abonnements im Dienstnamespace oder eine leere Auflistung zurück, wenn kein Abonnement vorhanden ist.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var SubscriptionsWithMessages = namespaceManager.GetSubscriptions ("Name_des_themas", "MessageCount Gt 0"); Var SubscriptionsStartsWith = namespaceManager.GetSubscriptions ("Name_des_themas", $"" StartsWith "(Pfad, 'Abonnement') Eq"true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync topicPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft asynchron eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync (string topicPath, string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt; GetSubscriptionsAsync(string topicPath, string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetSubscriptionsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubscriptionsAsync (topicPath As String, filter As String) As Task(Of IEnumerable(Of SubscriptionDescription))" />
      <MemberSignature Language="F#" Value="member this.GetSubscriptionsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;" Usage="namespaceManager.GetSubscriptionsAsync (topicPath, filter)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="filter">Die Zeichenfolge, die zum Filtern von Abonnements abgerufen werden sollen.</param>
        <summary>Ruft asynchron eine aufzählbare Auflistung aller Abonnements im Dienstnamespace ein.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var SubscriptionsWithMessages = "await" namespaceManager.GetSubscriptionsAsync ("Name_des_themas", "MessageCount Gt 0"); Var SubscriptionsStartsWith = "await" namespaceManager.GetSubscriptionsAsync ("Name_des_themas", $"" StartsWith "(Pfad, 'Abonnement') Eq"true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription GetTopic (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription GetTopic(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopic (path As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.GetTopic : string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.GetTopic path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft das Thema aus dem Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> Verweis auf das Thema oder ein <see cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException" /> -Ausnahme aus, wenn das Thema nicht im Dienstnamespace vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <paramref name="path" />ist leer oder null.</exception>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Das Thema im Dienstnamespace ist nicht vorhanden.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopicAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicAsync (path As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopicAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopicAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ruft asynchron Thema Dienstnamespace ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics () As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : unit -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine Auflistung der Themen in einem Dienstnamespace ab.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung der Themen, unter dem aktuellen Namespace oder eine leere Auflistung zurück, wenn kein Thema vorhanden ist.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.TimeoutException">Timeout des Vorgangs. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie müssen möglicherweise den Wert erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Die <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> Objekt verfügt nicht über ausreichende Berechtigungen zum Ausführen dieses Vorgangs. Sie sollten prüfen, um sicherzustellen, dass Ihre <see cref="T:Microsoft.ServiceBus.NamespaceManager" /> verfügt über den richtigen <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.TokenProvider" /> Anmeldeinformationen zum Ausführen dieses Vorgangs.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; GetTopics(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopics(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopics (filter As String) As IEnumerable(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.GetTopics : string -&gt; seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.GetTopics filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Die Zeichenfolge, die zum Filtern der Themen abgerufen werden sollen.</param>
        <summary>Ruft eine Auflistung von Themen in einem Dienstnamespace mit dem angegebenen Filter ab. Sie können durch eine Kombination von Entitätsname (einschließlich beginnt mit), Entität Länge (Gt oder Lt), erstellt, aktualisiert und Zugriffs-Zeit (Gt oder Lt) filtern.</summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerable`1" /> -Objekt, stellt die Auflistung der Themen, unter dem aktuellen Namespace oder eine leere Auflistung zurück, wenn kein Thema vorhanden ist.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var TopicsWithMessages = namespaceManager.GetTopics ("MessageCount Gt 0"); Var TopicsStartsWith = namespaceManager.GetTopics ($"" StartsWith "(Pfad,"Thema") Eq" true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync () As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Eine Auflistung der Themen in einem Dienstnamespace asynchron abgerufen.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTopicsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt; GetTopicsAsync(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetTopicsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTopicsAsync (filter As String) As Task(Of IEnumerable(Of TopicDescription))" />
      <MemberSignature Language="F#" Value="member this.GetTopicsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;" Usage="namespaceManager.GetTopicsAsync filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Die Zeichenfolge, die zum Filtern der Themen abgerufen werden sollen.</param>
        <summary>Eine Auflistung der Themen in einem Dienstnamespace asynchron abgerufen.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>
            Filtern von ausdrucksformaten: {aus} {logischer Operator} {Value} und {Filterausdruck} {Funktion} {logischer Operator} {Value} und {Filterausdruck}
                                        -----------------------------------------------------------------------------------------
            Verfügbare Eigenschaften: Pfad | ModifiedAt | AccessedAt | CreatedAt | MessageCount logische Operatoren: Eq | Ne | Gt | Ge | Lt | LE  
            Wert: Geben Sie ein Wert der entsprechenden Eigenschaft Funktionen: "StartsWith" ({aus}, {Value})
            </remarks>
        <example>
          <code>
            Var TopicsWithMessages = "await" namespaceManager.GetTopicsAsync ("MessageCount Gt 0"); Var TopicsStartsWith = "await" namespaceManager.GetTopicsAsync ($"" StartsWith "(Pfad,"Thema") Eq" true "");
            </code>
        </example>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</summary>
        <returns>Eine Zeichenfolge, die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfoAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetVersionInfoAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetVersionInfoAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron Ruft eine Zeichenfolge im Format "YYYY-MM", die die maximal unterstützte Protokollversion angibt, die den Server oder-Dienst verarbeiten kann.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.ServiceBus.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Zeichenfolge im Format "YYYY-MM", die die Client-Protokollversion angibt.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExists">
      <MemberSignature Language="C#" Value="public bool QueueExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool QueueExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.QueueExists : string -&gt; bool" Usage="namespaceManager.QueueExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Bestimmt, ob eine Warteschlange im Dienstnamespace vorhanden ist.</summary>
        <returns>"true", wenn eine Warteschlange im Dienstnamespace vorhanden ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueueExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; QueueExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; QueueExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.QueueExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function QueueExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.QueueExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.QueueExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad der Warteschlange relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ermittelt asynchron, ob eine Warteschlange im Dienstnamespace vorhanden ist.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExists">
      <MemberSignature Language="C#" Value="public bool RelayExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool RelayExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.RelayExists : string -&gt; bool" Usage="namespaceManager.RelayExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Bestimmt, ob ein Relay im Dienstnamespace vorhanden ist.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelayExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; RelayExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; RelayExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RelayExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RelayExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RelayExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.RelayExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceBus.NamespaceManager/&lt;RelayExistsAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Relays relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ermittelt asynchron, ob ein Relay im Dienstnamespace vorhanden ist.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RenameQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription RenameQueue(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueue (path As String, newPath As String) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.RenameQueue : string * string -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.RenameQueue (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu einer vorhandenen Warteschlange.</param>
        <param name="newPath">Der neue Pfad an die Warteschlange umbenannt.</param>
        <summary>Benennt eine Warteschlange in einem Namespace an.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn die Quellwarteschlange mit dem angegebenen Pfad nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn die Zielwarteschlange mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; RenameQueueAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameQueueAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameQueueAsync (path As String, newPath As String) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameQueueAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.RenameQueueAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad zu einer vorhandenen Warteschlange.</param>
        <param name="newPath">Der neue Pfad an die Warteschlange umbenannt.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameQueue(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn die Quellwarteschlange mit dem angegebenen Pfad nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn die Zielwarteschlange mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription RenameTopic(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopic (path As String, newPath As String) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.RenameTopic : string * string -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.RenameTopic (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf ein vorhandenes Thema.</param>
        <param name="newPath">Der neue Pfad an das umbenannte Thema.</param>
        <summary>Benennt ein Thema in einem Namespace an.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn das quellthema mit dem angegebenen Pfad nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn das Zielthema mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenameTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync (string path, string newPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; RenameTopicAsync(string path, string newPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RenameTopicAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RenameTopicAsync (path As String, newPath As String) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.RenameTopicAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.RenameTopicAsync (path, newPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="newPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf ein vorhandenes Thema.</param>
        <param name="newPath">Der neue Pfad an das umbenannte Thema.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RenameTopic(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn <paramref name="path" /> ist null oder leer.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn die Länge des <paramref name="path" /> beträgt mehr als 290 Zeichen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Klasse. Sie können den Wert der erhöhen die <see cref="P:Microsoft.ServiceBus.NamespaceManagerSettings.OperationTimeout" /> Eigenschaft, um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wird ausgelöst, wenn das quellthema mit dem angegebenen Pfad nicht vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityAlreadyExistsException">Wird ausgelöst, wenn das Zielthema mit dem gleichen Pfad innerhalb des gleichen Namespace vorhanden ist.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wird ausgelöst, wenn der Client die Anmeldeinformationen zum Ausführen des Vorgangs nicht besitzt.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wird ausgelöst, wenn ein interner Fehler oder unerwartete Ausnahme auftritt.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisher">
      <MemberSignature Language="C#" Value="public void RestorePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RestorePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RestorePublisher (entityPath As String, publisher As String)" />
      <MemberSignature Language="F#" Value="member this.RestorePublisher : string * string -&gt; unit" Usage="namespaceManager.RestorePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Ereignis-Hub Pfad unter dem der Verleger wurde gesperrt und muss wiederhergestellt werden. Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</param>
        <param name="publisher">Der gesperrten Herausgeber.</param>
        <summary>Entfernt den Verleger aus der Sperrliste Event Hubs.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestorePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestorePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestorePublisherAsync (entityPath As String, publisher As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestorePublisherAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.RestorePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Ereignis-Hub Pfad unter dem der Verleger wurde gesperrt und muss wiederhergestellt werden. Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</param>
        <param name="publisher">Der gesperrten Herausgeber.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RestorePublisher(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisher">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription RevokePublisher(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisher (entityPath As String, publisher As String) As RevokedPublisherDescription" />
      <MemberSignature Language="F#" Value="member this.RevokePublisher : string * string -&gt; Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" Usage="namespaceManager.RevokePublisher (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RevokedPublisherDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Event Hub-Pfad, unter dem der Verleger aufgehoben werden muss. Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</param>
        <param name="publisher">Der Herausgeber aufzuheben.</param>
        <summary>Fügt den Verleger wurde der Sperrliste Event Hubs.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.RevokedPublisherDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RevokePublisherAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync (string entityPath, string publisher);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt; RevokePublisherAsync(string entityPath, string publisher) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisherAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RevokePublisherAsync (entityPath As String, publisher As String) As Task(Of RevokedPublisherDescription)" />
      <MemberSignature Language="F#" Value="member this.RevokePublisherAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;" Usage="namespaceManager.RevokePublisherAsync (entityPath, publisher)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RevokedPublisherDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityPath" Type="System.String" />
        <Parameter Name="publisher" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityPath">Event Hub-Pfad, unter dem der Verleger aufgehoben werden muss. Weitere Informationen finden Sie unter <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />.</param>
        <param name="publisher">Der Herausgeber aufzuheben.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.ServiceBus.NamespaceManager.RevokePublisher(System.String,System.String)" />.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.ServiceBus.NamespaceManagerSettings" Usage="Microsoft.ServiceBus.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Namespace-Dienstclient Einstellungen ab.</summary>
        <value>Ein <see cref="T:Microsoft.ServiceBus.NamespaceManagerSettings" /> Objekt, das die Clienteinstellungen des Dienst-Namespace darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExists">
      <MemberSignature Language="C#" Value="public bool SubscriptionExists (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool SubscriptionExists(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExists(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExists (topicPath As String, name As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExists : string * string -&gt; bool" Usage="namespaceManager.SubscriptionExists (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Bestimmt, ob ein Abonnement im Dienstnamespace vorhanden ist.</summary>
        <returns>True, wenn ein Abonnement vorhanden ist, im Dienstnamespace. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; SubscriptionExistsAsync (string topicPath, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; SubscriptionExistsAsync(string topicPath, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.SubscriptionExistsAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubscriptionExistsAsync (topicPath As String, name As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SubscriptionExistsAsync : string * string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.SubscriptionExistsAsync (topicPath, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="topicPath" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="topicPath">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <param name="name">Der Name des Abonnements.</param>
        <summary>Ermittelt asynchron, ob ein Abonnement im Dienstnamespace vorhanden ist.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExists">
      <MemberSignature Language="C#" Value="public bool TopicExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TopicExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TopicExists : string -&gt; bool" Usage="namespaceManager.TopicExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Bestimmt, ob im Dienstnamespace ein Thema vorhanden ist.</summary>
        <returns>"true", wenn ein Thema vorhanden, im Dienstnamespace ist; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; TopicExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; TopicExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.TopicExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function TopicExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.TopicExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.TopicExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad des Themas relativ zur Basisadresse Diensts-Namespace.</param>
        <summary>Ermittelt asynchron, ob im Dienstnamespace ein Thema vorhanden ist.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroup">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription UpdateConsumerGroup(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroup(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroup (description As ConsumerGroupDescription) As ConsumerGroupDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroup : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" Usage="namespaceManager.UpdateConsumerGroup description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.ConsumerGroupDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" /> Objekt, das die aktualisierte Informationen enthält.</param>
        <summary>Aktualisiert eine Event Hubs-Consumer-Gruppe.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateConsumerGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync (Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt; UpdateConsumerGroupAsync(class Microsoft.ServiceBus.Messaging.ConsumerGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateConsumerGroupAsync(Microsoft.ServiceBus.Messaging.ConsumerGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateConsumerGroupAsync (description As ConsumerGroupDescription) As Task(Of ConsumerGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateConsumerGroupAsync : Microsoft.ServiceBus.Messaging.ConsumerGroupDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;" Usage="namespaceManager.UpdateConsumerGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.ConsumerGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.ConsumerGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die Beschreibung für den Consumer-Gruppe.</param>
        <summary>Aktualisiert asynchron die consumergruppe.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHub">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.EventHubDescription UpdateEventHub(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHub(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHub (description As EventHubDescription) As EventHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHub : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; Microsoft.ServiceBus.Messaging.EventHubDescription" Usage="namespaceManager.UpdateEventHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.EventHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" /> Objekt, das die aktualisierte Informationen enthält.</param>
        <summary>Aktualisiert den Event Hub.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.EventHubDescription" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEventHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync (Microsoft.ServiceBus.Messaging.EventHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.EventHubDescription&gt; UpdateEventHubAsync(class Microsoft.ServiceBus.Messaging.EventHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateEventHubAsync(Microsoft.ServiceBus.Messaging.EventHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEventHubAsync (description As EventHubDescription) As Task(Of EventHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateEventHubAsync : Microsoft.ServiceBus.Messaging.EventHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;" Usage="namespaceManager.UpdateEventHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.EventHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.EventHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Der Hub-Beschreibung des Ereignisses.</param>
        <summary>Asynchron aktualisiert den Event Hub.</summary>
        <returns>Die Aufgabe, die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueue">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.QueueDescription UpdateQueue(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueue(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueue (description As QueueDescription) As QueueDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateQueue : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; Microsoft.ServiceBus.Messaging.QueueDescription" Usage="namespaceManager.UpdateQueue description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.QueueDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt der Warteschlange aktualisiert werden.</param>
        <summary>Können Sie die Warteschlange zu aktualisieren.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> von der Warteschlange aktualisiert.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateQueueAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync (Microsoft.ServiceBus.Messaging.QueueDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.QueueDescription&gt; UpdateQueueAsync(class Microsoft.ServiceBus.Messaging.QueueDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateQueueAsync(Microsoft.ServiceBus.Messaging.QueueDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateQueueAsync (description As QueueDescription) As Task(Of QueueDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateQueueAsync : Microsoft.ServiceBus.Messaging.QueueDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;" Usage="namespaceManager.UpdateQueueAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.QueueDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.QueueDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.QueueDescription" /> -Objekt, beschreibt der Warteschlange aktualisiert werden.</param>
        <summary>Asynchron können Sie die Warteschlange zu aktualisieren.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelay">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.RelayDescription UpdateRelay(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelay(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelay (description As RelayDescription) As RelayDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateRelay : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; Microsoft.ServiceBus.Messaging.RelayDescription" Usage="namespaceManager.UpdateRelay description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.RelayDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> -Objekt, das aktualisierte Relay beschreibt.</param>
        <summary>Upddates einen relayendpunkt.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateRelayAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync (Microsoft.ServiceBus.Messaging.RelayDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.RelayDescription&gt; UpdateRelayAsync(class Microsoft.ServiceBus.Messaging.RelayDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateRelayAsync(Microsoft.ServiceBus.Messaging.RelayDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRelayAsync (description As RelayDescription) As Task(Of RelayDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateRelayAsync : Microsoft.ServiceBus.Messaging.RelayDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;" Usage="namespaceManager.UpdateRelayAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.RelayDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.RelayDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.RelayDescription" /> -Objekt, das aktualisierte Relay beschreibt.</param>
        <summary>Asynchron Upddates einen relayendpunkt.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscription">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.SubscriptionDescription UpdateSubscription(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscription(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscription (description As SubscriptionDescription) As SubscriptionDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscription : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; Microsoft.ServiceBus.Messaging.SubscriptionDescription" Usage="namespaceManager.UpdateSubscription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.SubscriptionDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, das Abonnement zu aktualisierenden beschreibt.</param>
        <summary>Ermöglicht es Ihnen, beim Aktualisieren des Abonnements.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> des aktualisierten Abonnements.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSubscriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync (Microsoft.ServiceBus.Messaging.SubscriptionDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt; UpdateSubscriptionAsync(class Microsoft.ServiceBus.Messaging.SubscriptionDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateSubscriptionAsync(Microsoft.ServiceBus.Messaging.SubscriptionDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSubscriptionAsync (description As SubscriptionDescription) As Task(Of SubscriptionDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateSubscriptionAsync : Microsoft.ServiceBus.Messaging.SubscriptionDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;" Usage="namespaceManager.UpdateSubscriptionAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.SubscriptionDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.SubscriptionDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.SubscriptionDescription" /> -Objekt, das Abonnement zu aktualisierenden beschreibt.</param>
        <summary>Asynchron können Sie das Abonnement aktualisieren.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopic">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.TopicDescription UpdateTopic(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopic(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopic (description As TopicDescription) As TopicDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateTopic : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; Microsoft.ServiceBus.Messaging.TopicDescription" Usage="namespaceManager.UpdateTopic description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TopicDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, das im Thema zu aktualisierenden beschreibt.</param>
        <summary>Ermöglicht Ihnen das Thema zu aktualisieren.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> des aktuellen Themas.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTopicAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync (Microsoft.ServiceBus.Messaging.TopicDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceBus.Messaging.TopicDescription&gt; UpdateTopicAsync(class Microsoft.ServiceBus.Messaging.TopicDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.NamespaceManager.UpdateTopicAsync(Microsoft.ServiceBus.Messaging.TopicDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTopicAsync (description As TopicDescription) As Task(Of TopicDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateTopicAsync : Microsoft.ServiceBus.Messaging.TopicDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;" Usage="namespaceManager.UpdateTopicAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceBus.Messaging.TopicDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.ServiceBus.Messaging.TopicDescription" />
      </Parameters>
      <Docs>
        <param name="description">Ein <see cref="T:Microsoft.ServiceBus.Messaging.TopicDescription" /> -Objekt, das im Thema zu aktualisierenden beschreibt.</param>
        <summary>Asynchron können Sie das Thema zu aktualisieren.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>