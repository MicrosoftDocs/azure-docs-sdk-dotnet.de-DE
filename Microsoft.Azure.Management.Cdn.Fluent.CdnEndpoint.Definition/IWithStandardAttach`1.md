<Type Name="IWithStandardAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithStandardAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachableStandard&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithStandardAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachableStandard`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithStandardAttach(Of ParentT)&#xA;Implements IAttachableStandard(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithStandardAttach&lt;'ParentT&gt; = interface&#xA;    interface IAttachableStandard&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IAttachableStandard&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten Elements CDN-Profildefinition wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die letzte Phase des CDN-Profils Standard Akamai oder Standard Verizon Endpunktdefinition.
            Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder die CDN-Endpunkt Profildefinition an das übergeordnete Element CDN-Profildefinition angefügt werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithCompressionEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithCompressionEnabled (bool compressionEnabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithCompressionEnabled(bool compressionEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithCompressionEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCompressionEnabled (compressionEnabled As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCompressionEnabled : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithCompressionEnabled compressionEnabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="compressionEnabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="compressionEnabled">Bei "true" wird die Komprimierung aktiviert werden.</param>
        <summary>
            Legt den Komprimierungsstatus fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithContentTypesToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithContentTypesToCompress (System.Collections.Generic.ISet&lt;string&gt; contentTypesToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithContentTypesToCompress(class System.Collections.Generic.ISet`1&lt;string&gt; contentTypesToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithContentTypesToCompress(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypesToCompress (contentTypesToCompress As ISet(Of String)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypesToCompress : System.Collections.Generic.ISet&lt;string&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithContentTypesToCompress contentTypesToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentTypesToCompress" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentTypesToCompress">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithContentTypeToCompress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithContentTypeToCompress (string contentTypeToCompress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithContentTypeToCompress(string contentTypeToCompress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithContentTypeToCompress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithContentTypeToCompress (contentTypeToCompress As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithContentTypeToCompress : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithContentTypeToCompress contentTypeToCompress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentTypeToCompress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="contentTypeToCompress">Einen Inhaltstyp zu komprimieren, um zur Liste hinzuzufügen.</param>
        <summary>
            Gibt einen einzelnen Inhaltstyp zu komprimieren.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCustomDomain (hostName As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">eine benutzerdefinierte Domäne-Hostnamen.</param>
        <summary>
            Fügt eine neue benutzerdefinierte CDN-Domäne innerhalb eines Endpunkts an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode countryCode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCode As CountryISOCode) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilter (relativePath, action, countryCode)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCode" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode" />
      </Parameters>
      <Docs>
        <param name="relativePath">Ein relativer Pfad.</param>
        <param name="action">Eine geografische Filteraktion.</param>
        <param name="countryCode">Ein ISO-2 Buchstaben bestehender Ländercode.</param>
        <summary>
            Die Liste der geografischen Filter hinzugefügt einen einzelnen Eintrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilter (string relativePath, Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilter(string relativePath, valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions action, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; countryCodes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithGeoFilter(System.String,Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilter (relativePath As String, action As GeoFilterActions, countryCodes As IList(Of CountryISOCode)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilter : string * Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilter (relativePath, action, countryCodes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="action" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilterActions" />
        <Parameter Name="countryCodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.CountryISOCode&gt;" />
      </Parameters>
      <Docs>
        <param name="relativePath">Ein relativer Pfad.</param>
        <param name="action">Der Aktionswert einer.</param>
        <param name="countryCodes">eine Liste der ISO-2 Buchstaben Land.</param>
        <summary>
            Die Geo-Filter-Liste für die angegebene Liste fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithGeoFilters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithGeoFilters (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithGeoFilters(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; geoFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithGeoFilters(System.Collections.Generic.IList{Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGeoFilters (geoFilters As IList(Of GeoFilter)) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGeoFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithGeoFilters geoFilters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="geoFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="geoFilters">Die geografische filtert die Liste festlegen.</param>
        <summary>
            Die Liste der geografischen Filter fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHostHeader">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithHostHeader (string hostHeader);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithHostHeader(string hostHeader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithHostHeader(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostHeader (hostHeader As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHostHeader : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHostHeader hostHeader" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostHeader" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostHeader">ein Hostheader.</param>
        <summary>
            Gibt den Host-Header an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithHttpAllowed (bool httpAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpAllowed(bool httpAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithHttpAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpAllowed (httpAllowed As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpAllowed httpAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpAllowed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="httpAllowed">Bei "true" wird der HTTP-Datenverkehr zugelassen.</param>
        <summary>
            Gibt an, ob HTTP-Datenverkehr zugelassen wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithHttpPort (int httpPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpPort(int32 httpPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpPort (httpPort As Integer) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpPort httpPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="httpPort">eine Portnummer an.</param>
        <summary>
            Gibt den Port für HTTP-Datenverkehr.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsAllowed">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithHttpsAllowed (bool httpsAllowed);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpsAllowed(bool httpsAllowed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithHttpsAllowed(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsAllowed (httpsAllowed As Boolean) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsAllowed : bool -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpsAllowed httpsAllowed" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpsAllowed" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="httpsAllowed">Wenn Sie auf "true" Https-Datenverkehr zulässig.</param>
        <summary>
            Gibt an, ob HTTPS-Datenverkehr zugelassen wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithHttpsPort (int httpsPort);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithHttpsPort(int32 httpsPort) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsPort (httpsPort As Integer) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsPort : int -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithHttpsPort httpsPort" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="httpsPort" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="httpsPort">HTTPS-Portnummer.</param>
        <summary>
            Gibt den Port für HTTPS-Datenverkehr.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithOriginPath">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithOriginPath (string originPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithOriginPath(string originPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithOriginPath(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOriginPath (originPath As String) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithOriginPath : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithOriginPath originPath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="originPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originPath">ein Ursprungspfad.</param>
        <summary>
            Gibt den Ursprungspfad.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithQueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt; WithQueryStringCachingBehavior (Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1&lt;!ParentT&gt; WithQueryStringCachingBehavior(valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior cachingBehavior) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach`1.WithQueryStringCachingBehavior(Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithQueryStringCachingBehavior (cachingBehavior As QueryStringCachingBehavior) As IWithStandardAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithQueryStringCachingBehavior : Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;'ParentT&gt;" Usage="iWithStandardAttach.WithQueryStringCachingBehavior cachingBehavior" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.Definition.IWithStandardAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingBehavior" Type="Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior" />
      </Parameters>
      <Docs>
        <param name="cachingBehavior">Das Zwischenspeichern von Abfragezeichenfolgen festzulegende Verhaltenswert.</param>
        <summary>
            Legt die Abfragezeichenfolge, die Verhalten beim Zwischenspeichern fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>