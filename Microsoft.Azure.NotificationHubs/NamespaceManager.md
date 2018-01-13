<Type Name="NamespaceManager" FullName="Microsoft.Azure.NotificationHubs.NamespaceManager">
  <TypeSignature Language="C#" Value="public sealed class NamespaceManager" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NamespaceManager extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NamespaceManager" />
  <TypeSignature Language="F#" Value="type NamespaceManager = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit den angegebenen Adressen.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adressen Feld null ist.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
        <exception cref="T:System.UriFormatException">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager addresses" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit den angegebenen Dienst Namespace-URI-Basisadressen.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adressen Feld null ist.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace Dienstadresse.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adresse null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager address" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse. </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adresse null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of String), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Einstellungen.</summary>
        <remarks>
            Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist kein, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adressen Itse sein muss LF
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adresse oder Einstellungen ist null.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
        <exception cref="T:System.UriFormatException">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;string&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;string&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Die vollständige Adressen des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Adressen und Anbieter von Sicherheitstoken.</summary>
        <remarks>
            Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adressen Feld null ist.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
        <exception cref="T:System.UriFormatException">Ausgelöst, wenn die Adresse nicht richtig formatiert ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (addresses As IEnumerable(Of Uri), settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Einstellungen.</summary>
        <remarks>
            Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adressen oder Einstellungen ist null.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (System.Collections.Generic.IEnumerable&lt;Uri&gt; addresses, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class System.Uri&gt; addresses, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Collections.Generic.IEnumerable{System.Uri},Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : seq&lt;Uri&gt; * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (addresses, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addresses" Type="System.Collections.Generic.IEnumerable&lt;System.Uri&gt;" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="addresses">Der vollständige URI-Adressen des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Dienst Namespace-URI-Basisadressen und Anbieter von Sicherheitstoken.</summary>
        <remarks>
            Obwohl es nicht zulässig ist die Namespace-Adressen Pfade einschließt, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen von Basisadressen Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, dass die Anmeldeinformationen, die Sie angeben, auf der Basis-Adressen werden Self-Service
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn Adressen null ist.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Typ nicht um einen unterstützten Typ der Anmeldeinformationen ist.
            Finden Sie unter <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> ausführliche Informationen zu den unterstützten Typen.</exception>
        <exception cref="T:System.ArgumentException">Ausgelöst, wenn die Liste der Adressen null oder leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As String, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt.</summary>
        <remarks>
            Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="settings" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (string address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.String,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : string * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.String" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige Adresse des dienstnamespaces.</param>
        <param name="tokenProvider">Der Sicherheitstokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit dem angegebenen Namespace dienstbasisadresse und Anbieter von Sicherheitstoken.</summary>
        <remarks>
            Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie Anmeldeinformationen angeben, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="token provider" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.NamespaceManagerSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (address As Uri, settings As NamespaceManagerSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.NamespaceManagerSettings -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="settings" Type="Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <param name="settings">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> -Objekt, das enthält die <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.Credential" /> und <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.OperationTimeout" /> Eigenschaften.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt.</summary>
        <remarks>
            Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="settings" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceManager (Uri address, Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri address, class Microsoft.Azure.NotificationHubs.TokenProvider tokenProvider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.#ctor(System.Uri,Microsoft.Azure.NotificationHubs.TokenProvider)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NamespaceManager : Uri * Microsoft.Azure.NotificationHubs.TokenProvider -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="new Microsoft.Azure.NotificationHubs.NamespaceManager (address, tokenProvider)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="address" Type="System.Uri" />
        <Parameter Name="tokenProvider" Type="Microsoft.Azure.NotificationHubs.TokenProvider" />
      </Parameters>
      <Docs>
        <param name="address">Die vollständige URI-Adresse des dienstnamespaces.</param>
        <param name="tokenProvider">Das Sicherheitsobjekt Tokenanbieter.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> Klasse mit der angegebenen Service Namespace-URI-Basisadresse und <see cref="T:Microsoft.Azure.NotificationHubs.TokenProvider" /> Objekt.</summary>
        <remarks>
            Obwohl es nicht zulässig ist, Pfade in der Namespace-Adresse enthalten, können Sie die Anmeldeinformationen, die nur auf einige Unterebenen aus der Basisadresse Aktionen autorisiert angeben, d. h. es ist nicht erforderlich, die die Anmeldeinformationen, die Sie angeben, auf der Basis Adresse selbst sein
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <paramref name="address" /> oder <paramref name="token provider" /> ist NULL.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der Typ nicht um einen unterstützten Typ der Anmeldeinformationen ist.
            Finden Sie unter <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings.TokenProvider" /> ausführliche Informationen zu den unterstützten Typen.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="address" />enthält einen Pfad an die vollständige Adresse des Dienstnamespace angefügt.</exception>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public Uri Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Address" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As Uri" />
      <MemberSignature Language="F#" Value="member this.Address : Uri" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
    <Member MemberName="BeginGetVersionInfo">
      <MemberSignature Language="C#" Value="public IAsyncResult BeginGetVersionInfo (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.IAsyncResult BeginGetVersionInfo(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.BeginGetVersionInfo(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginGetVersionInfo (callback As AsyncCallback, state As Object) As IAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginGetVersionInfo : AsyncCallback * obj -&gt; IAsyncResult" Usage="namespaceManager.BeginGetVersionInfo (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" />-Delegat, der auf die Methode verweist, die bei Abschluss des Vorgangs aufgerufen werden soll.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, das Statusinformationen über den asynchronen Vorgang enthält. Dieses Objekt wird bei Abschluss des Vorgangs an den <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersioninfo(System.IAsyncResult)" />-Delegaten übergeben.</param>
        <summary>Asynchrone Version von <see cref="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo(System.String)" /> Methode.</summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> Objekt, das den asynchronen Vorgang zum Abrufen der Versionsinformationen verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</summary>
        <returns>Eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.NamespaceManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As NamespaceManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.NotificationHubs.NamespaceManager" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Verbindung unkompliziert verwendet.</param>
        <summary>Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" /> mithilfe der angegebenen Verbindungszeichenfolge.</summary>
        <returns>Eine neue Instanz von <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManager" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription CreateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.CreateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen der neue benachrichtigungshub erstellt wird.</param>
        <summary>Erstellt einen neuen benachrichtigungs-Hub mit den angegebenen Eigenschaften der <paramref name="description" /> Parameter.</summary>
        <returns>Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt mit der Beschreibung des neu erstellten benachrichtigungs-Hub.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; CreateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.CreateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.CreateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, mit denen der neue benachrichtigungshub erstellt wird.</param>
        <summary>Erstellt asynchron einen neuen benachrichtigungs-Hub mit den angegebenen Eigenschaften der <paramref name="description" /> Parameter.</summary>
        <returns>Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt mit der Beschreibung des neu erstellten benachrichtigungs-Hub.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHub">
      <MemberSignature Language="C#" Value="public void DeleteNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteNotificationHub (path As String)" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHub : string -&gt; unit" Usage="namespaceManager.DeleteNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Notification Hub.</param>
        <summary>Löscht einen benachrichtigungs-Hub an der bereitgestellten <paramref name="path" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.DeleteNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteNotificationHubAsync (path As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteNotificationHubAsync : string -&gt; System.Threading.Tasks.Task" Usage="namespaceManager.DeleteNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Notification Hub.</param>
        <summary>Löscht asynchron einen benachrichtigungs-Hub an der bereitgestellten <paramref name="path" />.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteInstallation">
      <MemberSignature Language="C#" Value="public void EndDeleteInstallation (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteInstallation(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteInstallation(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteInstallation (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteInstallation : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteInstallation result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Der Verweis auf die ausstehende asynchrone Anforderung, die abgewartet werden soll.</param>
        <summary>
            Wartet, bis zum Abschluss der Installation steht asynchronen Löschvorgang.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteRegistration">
      <MemberSignature Language="C#" Value="public void EndDeleteRegistration (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EndDeleteRegistration(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndDeleteRegistration(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Sub EndDeleteRegistration (result As IAsyncResult)" />
      <MemberSignature Language="F#" Value="member this.EndDeleteRegistration : IAsyncResult -&gt; unit" Usage="namespaceManager.EndDeleteRegistration result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das das Ergebnis des Löschvorgangs Registrierung darstellt.</param>
        <summary>Beendet eine asynchrone Anforderung, eine Registrierung zu löschen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetVersionInfo">
      <MemberSignature Language="C#" Value="public string EndGetVersionInfo (IAsyncResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string EndGetVersionInfo(class System.IAsyncResult result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.EndGetVersionInfo(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndGetVersionInfo (result As IAsyncResult) As String" />
      <MemberSignature Language="F#" Value="member this.EndGetVersionInfo : IAsyncResult -&gt; string" Usage="namespaceManager.EndGetVersionInfo result" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="result" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="result">Ein <see cref="T:System.IAsyncResult" /> Objekt, das das Ergebnis des Get-Versionsinformationen darstellt.</param>
        <summary>Beendet eine asynchrone Anforderung an die Versionsinformationen abgerufen werden.</summary>
        <returns>Die Versionsinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription GetNotificationHub(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHub(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHub (path As String) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHub : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.GetNotificationHub path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Dienstnamespace.</param>
        <summary>Ruft die Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace ab.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> aus dem Dienstnamespace.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubAsync (path As String) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Dienstnamespace.</param>
        <summary>Ruft Sie die Beschreibung des benachrichtigungs-Hub asynchron aus dem Dienstnamespace ab.</summary>
        <returns>Der asynchrone Vorgang, der die Beschreibung des benachrichtigungs-Hub von dienstnamespaces abruft.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync (string jobId, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; GetNotificationHubJobAsync(string jobId, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobAsync (jobId As String, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.GetNotificationHubJobAsync (jobId, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Auftrags.</param>
        <param name="notificationHubPath">Der Pfad auf den Notification Hub.</param>
        <summary>Ruft asynchron eine angegebene Notification Hubs-Auftrag ab.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubJobsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync (string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt; GetNotificationHubJobsAsync(string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubJobsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubJobsAsync (notificationHubPath As String) As Task(Of IEnumerable(Of NotificationHubJob))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubJobsAsync : string -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;" Usage="namespaceManager.GetNotificationHubJobsAsync notificationHubPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="notificationHubPath">Der Pfad auf den Notification Hub.</param>
        <summary>Asynchron Ruft einen Satz von alle Notification Hubs Aufträge ab.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; GetNotificationHubs() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubs" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubs () As IEnumerable(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubs : unit -&gt; seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.GetNotificationHubs " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft die Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace ab.</summary>
        <returns>Die Liste der Beschreibung des benachrichtigungs-Hub aus dem Dienstnamespace.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNotificationHubsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt; GetNotificationHubsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetNotificationHubsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNotificationHubsAsync () As Task(Of IEnumerable(Of NotificationHubDescription))" />
      <MemberSignature Language="F#" Value="member this.GetNotificationHubsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;" Usage="namespaceManager.GetNotificationHubsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft Sie die Beschreibung des benachrichtigungs-Hub asynchron aus dem Dienstnamespace ab.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVersionInfo">
      <MemberSignature Language="C#" Value="public string GetVersionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetVersionInfo() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfo () As String" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfo : unit -&gt; string" Usage="namespaceManager.GetVersionInfo " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.GetVersionInfoAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetVersionInfoAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetVersionInfoAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="namespaceManager.GetVersionInfoAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
    <Member MemberName="NotificationHubExists">
      <MemberSignature Language="C#" Value="public bool NotificationHubExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool NotificationHubExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExists (path As String) As Boolean" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExists : string -&gt; bool" Usage="namespaceManager.NotificationHubExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Notification Hub.</param>
        <summary>Bestimmt, ob es ein benachrichtigungs-Hub an der angegebenen <paramref name="path" /> im Dienstnamespace.</summary>
        <returns>True, wenn es ein benachrichtigungs-Hub an der angegebenen <paramref name="path" /> im Dienstnamespace; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; NotificationHubExistsAsync (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;bool&gt; NotificationHubExistsAsync(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.NotificationHubExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function NotificationHubExistsAsync (path As String) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NotificationHubExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="namespaceManager.NotificationHubExistsAsync path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path">Der Pfad auf den Notification Hub.</param>
        <summary>Ermittelt asynchron, ob ein benachrichtigungs-Hub, an der angegebenen vorliegt <paramref name="path" /> im Dienstnamespace.</summary>
        <returns>Der asynchrone Vorgang.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtocolVersion">
      <MemberSignature Language="C#" Value="public const string ProtocolVersion;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string ProtocolVersion" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberSignature Language="VB.NET" Value="Public Const ProtocolVersion As String " />
      <MemberSignature Language="F#" Value="val mutable ProtocolVersion : string" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.ProtocolVersion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Zeichenfolge im Format "YYYY-MM", die der Client-Protokollversion angibt.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.NamespaceManagerSettings Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As NamespaceManagerSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" Usage="Microsoft.Azure.NotificationHubs.NamespaceManager.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NamespaceManagerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Namespace-Dienstclient Einstellungen ab.</summary>
        <value>Ein <see cref="T:Microsoft.Azure.NotificationHubs.NamespaceManagerSettings" /> Objekt, das die Clienteinstellungen des Dienst-Namespace darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitNotificationHubJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync (Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubJob&gt; SubmitNotificationHubJobAsync(class Microsoft.Azure.NotificationHubs.NotificationHubJob job, string notificationHubPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.SubmitNotificationHubJobAsync(Microsoft.Azure.NotificationHubs.NotificationHubJob,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SubmitNotificationHubJobAsync (job As NotificationHubJob, notificationHubPath As String) As Task(Of NotificationHubJob)" />
      <MemberSignature Language="F#" Value="member this.SubmitNotificationHubJobAsync : Microsoft.Azure.NotificationHubs.NotificationHubJob * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;" Usage="namespaceManager.SubmitNotificationHubJobAsync (job, notificationHubPath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.NotificationHubs.NotificationHubJob" />
        <Parameter Name="notificationHubPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="job">Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubJob" /> Objekt, das den Auftrag zum Übermitteln von darstellt.</param>
        <param name="notificationHubPath">Der Pfad auf den Notification Hub.</param>
        <summary>Sendet einen benachrichtigungs-Hub-Auftrag für die Verarbeitung an.</summary>
        <returns>Gibt <see cref="T:System.Threading.Tasks.Task`1" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHub">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.NotificationHubs.NotificationHubDescription UpdateNotificationHub(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHub(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHub (description As NotificationHubDescription) As NotificationHubDescription" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHub : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="namespaceManager.UpdateNotificationHub description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.NotificationHubDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, die mit denen benachrichtigungshub aktualisiert werden.</param>
        <summary>Aktualisiert einen vorhandenen benachrichtigungs-Hub an den im angegebenen Pfad die <paramref name="description" /> Parameter. Alle Notification Hub-Eigenschaften werden überschrieben, mit denen angegeben wird, der <paramref name="description" /> Parameter. </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt, das eine Beschreibung des aktualisierten benachrichtigungs-Hub enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateNotificationHubAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync (Microsoft.Azure.NotificationHubs.NotificationHubDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt; UpdateNotificationHubAsync(class Microsoft.Azure.NotificationHubs.NotificationHubDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NamespaceManager.UpdateNotificationHubAsync(Microsoft.Azure.NotificationHubs.NotificationHubDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNotificationHubAsync (description As NotificationHubDescription) As Task(Of NotificationHubDescription)" />
      <MemberSignature Language="F#" Value="member this.UpdateNotificationHubAsync : Microsoft.Azure.NotificationHubs.NotificationHubDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;" Usage="namespaceManager.UpdateNotificationHubAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.NotificationHubs.NotificationHubDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
      </Parameters>
      <Docs>
        <param name="description">Das Beschreibungsobjekt für beschreiben die Attribute, die mit denen benachrichtigungshub aktualisiert werden.</param>
        <summary>Aktualisiert asynchron an den im angegebenen Pfad ein vorhandenen benachrichtigungs-Hub der <paramref name="description" /> Parameter. Alle Notification Hub-Eigenschaften werden überschrieben, mit denen angegeben wird, der <paramref name="description" /> Parameter.</summary>
        <returns>Ein <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> Objekt, das eine Beschreibung des aktualisierten benachrichtigungs-Hub enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>