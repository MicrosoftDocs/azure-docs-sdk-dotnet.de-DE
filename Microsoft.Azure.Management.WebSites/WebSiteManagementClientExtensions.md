<Type Name="WebSiteManagementClientExtensions" FullName="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class WebSiteManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebSiteManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebSiteManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type WebSiteManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für WebSiteManagementClient.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability CheckNameAvailability (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, Nullable&lt;bool&gt; isFqdn = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability CheckNameAvailability(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailability(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckNameAvailability (operations As IWebSiteManagementClient, name As String, type As String, Optional isFqdn As Nullable(Of Boolean) = null) As ResourceNameAvailability" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailability (operations, name, type, isFqdn)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name">
            Der Ressourcenname überprüfen.
            </param>
        <param name="type">
            Ressourcentyp zur Überprüfung verwendet. Folgende Werte sind möglich: "Website", "Slot", "HostingEnvironment"
            </param>
        <param name="isFqdn">
            Ist vollqualifizierte Domänenname.
            </param>
        <summary>
            Überprüfen Sie, ob der Name einer Ressource verfügbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüfen Sie, ob der Name einer Ressource verfügbar ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.CheckNameAvailabilityAsync (operations, name, type, isFqdn, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;CheckNameAvailabilityAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="name">
            Der Ressourcenname überprüfen.
            </param>
        <param name="type">
            Ressourcentyp zur Überprüfung verwendet. Folgende Werte sind möglich: "Website", "Slot", "HostingEnvironment"
            </param>
        <param name="isFqdn">
            Ist vollqualifizierte Domänenname.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüfen Sie, ob der Name einer Ressource verfügbar ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüfen Sie, ob der Name einer Ressource verfügbar ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.User GetPublishingUser (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.User GetPublishingUser(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUser(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPublishingUser (operations As IWebSiteManagementClient) As User" />
      <MemberSignature Language="F#" Value="static member GetPublishingUser : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUser operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.User</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Benutzer ruft veröffentlicht werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Benutzer ruft veröffentlicht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt; GetPublishingUserAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt; GetPublishingUserAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUserAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPublishingUserAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetPublishingUserAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetPublishingUserAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Benutzer ruft veröffentlicht werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Benutzer ruft veröffentlicht werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SourceControl GetSourceControl (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SourceControl GetSourceControl(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControl(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSourceControl (operations As IWebSiteManagementClient, sourceControlType As String) As SourceControl" />
      <MemberSignature Language="F#" Value="static member GetSourceControl : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Azure.Management.WebSites.Models.SourceControl" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControl (operations, sourceControlType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SourceControl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceControlType">
            Typ des Datenquellen-Steuerelements
            </param>
        <summary>
            Ruft die Datenquellen-Steuerelements token
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die Datenquellen-Steuerelements token
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; GetSourceControlAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; GetSourceControlAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControlAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSourceControlAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSourceControlAsync (operations, sourceControlType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetSourceControlAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceControlType">
            Typ des Datenquellen-Steuerelements
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Datenquellen-Steuerelements token
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die Datenquellen-Steuerelements token
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocations">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.DeploymentLocations GetSubscriptionDeploymentLocations (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations GetSubscriptionDeploymentLocations(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocations(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSubscriptionDeploymentLocations (operations As IWebSiteManagementClient) As DeploymentLocations" />
      <MemberSignature Language="F#" Value="static member GetSubscriptionDeploymentLocations : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.DeploymentLocations" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocations operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.DeploymentLocations</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocationsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt; GetSubscriptionDeploymentLocationsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt; GetSubscriptionDeploymentLocationsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocationsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSubscriptionDeploymentLocationsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.GetSubscriptionDeploymentLocationsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;GetSubscriptionDeploymentLocationsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegions (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegions(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegions(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGeoRegions (operations As IWebSiteManagementClient, Optional sku As String = null, Optional linuxWorkersEnabled As Nullable(Of Boolean) = null) As IPage(Of GeoRegion)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegions : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Nullable&lt;bool&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegions (operations, sku, linuxWorkersEnabled)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sku">
            Name der SKU, die zum Filtern der Regionen verwendet werden. Folgende Werte sind möglich: "Free", "Shared", "Basic", "Standard", "Premium", "PremiumV2", "Dynamic", "Isoliert"
            </param>
        <param name="linuxWorkersEnabled">
            Geben Sie &lt;Code&gt;"true"&lt;/code&gt; ggf. nur Regionen zu filtern, die Linux-Worker-Unterstützung.
            </param>
        <summary>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsAsync (operations, sku, linuxWorkersEnabled, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListGeoRegionsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sku">
            Name der SKU, die zum Filtern der Regionen verwendet werden. Folgende Werte sind möglich: "Free", "Shared", "Basic", "Standard", "Premium", "PremiumV2", "Dynamic", "Isoliert"
            </param>
        <param name="linuxWorkersEnabled">
            Geben Sie &lt;Code&gt;"true"&lt;/code&gt; ggf. nur Regionen zu filtern, die Linux-Worker-Unterstützung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegionsNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt; ListGeoRegionsNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGeoRegionsNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of GeoRegion)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt; ListGeoRegionsNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGeoRegionsNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListGeoRegionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListGeoRegionsNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der verfügbaren geografischen Regionen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffers">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffers (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffers(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffers(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPremierAddOnOffers (operations As IWebSiteManagementClient) As IPage(Of PremierAddOnOffer)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffers : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffers operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Listen Sie aller premier-Add-Angebote auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller premier-Add-Angebote auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller premier-Add-Angebote auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller premier-Add-Angebote auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffersNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt; ListPremierAddOnOffersNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListPremierAddOnOffersNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of PremierAddOnOffer)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Listen Sie aller premier-Add-Angebote auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller premier-Add-Angebote auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt; ListPremierAddOnOffersNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListPremierAddOnOffersNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListPremierAddOnOffersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListPremierAddOnOffersNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller premier-Add-Angebote auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller premier-Add-Angebote auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SkuInfos ListSkus (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SkuInfos ListSkus(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkus(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSkus (operations As IWebSiteManagementClient) As SkuInfos" />
      <MemberSignature Language="F#" Value="static member ListSkus : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Azure.Management.WebSites.Models.SkuInfos" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkus operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuInfos</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Listen Sie alle SKUs.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie alle SKUs.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt; ListSkusAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt; ListSkusAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkusAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSkusAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSkusAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSkusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie alle SKUs.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie alle SKUs.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControls">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControls (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControls(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControls(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSourceControls (operations As IWebSiteManagementClient) As IPage(Of SourceControl)" />
      <MemberSignature Language="F#" Value="static member ListSourceControls : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControls operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSourceControlsAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControlsNext (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; ListSourceControlsNext(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNext(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListSourceControlsNext (operations As IWebSiteManagementClient, nextPageLink As String) As IPage(Of SourceControl)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsNext : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsNextAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; ListSourceControlsNextAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNextAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListSourceControlsNextAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ListSourceControlsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ListSourceControlsNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Move">
      <MemberSignature Language="C#" Value="public static void Move (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Move(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Move(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Move (operations As IWebSiteManagementClient, resourceGroupName As String, moveResourceEnvelope As CsmMoveResourceEnvelope)" />
      <MemberSignature Language="F#" Value="static member Move : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Move (operations, resourceGroupName, moveResourceEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="moveResourceEnvelope">
            Objekt, das Verschieben die Ressource darstellt.
            </param>
        <summary>
            Verschieben von Ressourcen zwischen Ressourcengruppen.
            </summary>
        <remarks>
            Verschieben von Ressourcen zwischen Ressourcengruppen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.MoveAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.MoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;MoveAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="moveResourceEnvelope">
            Objekt, das Verschieben die Ressource darstellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verschieben von Ressourcen zwischen Ressourcengruppen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Verschieben von Ressourcen zwischen Ressourcengruppen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.User UpdatePublishingUser (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.User userDetails);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.User UpdatePublishingUser(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.User userDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUser(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.User)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdatePublishingUser (operations As IWebSiteManagementClient, userDetails As User) As User" />
      <MemberSignature Language="F#" Value="static member UpdatePublishingUser : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.User -&gt; Microsoft.Azure.Management.WebSites.Models.User" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUser (operations, userDetails)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.User</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="userDetails">
            Details des Benutzers veröffentlichen
            </param>
        <summary>
            Updates, die publishing Benutzer
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Updates, die publishing Benutzer
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt; UpdatePublishingUserAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.User userDetails, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt; UpdatePublishingUserAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.User userDetails, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUserAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.User,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdatePublishingUserAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.User * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdatePublishingUserAsync (operations, userDetails, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;UpdatePublishingUserAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="userDetails">
            Details des Benutzers veröffentlichen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Updates, die publishing Benutzer
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Updates, die publishing Benutzer
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.SourceControl UpdateSourceControl (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.SourceControl UpdateSourceControl(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControl(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSourceControl (operations As IWebSiteManagementClient, sourceControlType As String, requestMessage As SourceControl) As SourceControl" />
      <MemberSignature Language="F#" Value="static member UpdateSourceControl : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.SourceControl -&gt; Microsoft.Azure.Management.WebSites.Models.SourceControl" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControl (operations, sourceControlType, requestMessage)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SourceControl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceControlType">
            Typ des Datenquellen-Steuerelements
            </param>
        <param name="requestMessage">
            Token Quellinformationen für Steuerelement
            </param>
        <summary>
            Updates Source Control token
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Updates Source Control token
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; UpdateSourceControlAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt; UpdateSourceControlAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControlAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSourceControlAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.UpdateSourceControlAsync (operations, sourceControlType, requestMessage, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;UpdateSourceControlAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="sourceControlType">
            Typ des Datenquellen-Steuerelements
            </param>
        <param name="requestMessage">
            Token Quellinformationen für Steuerelement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Updates Source Control token
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Updates Source Control token
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.ValidateResponse Validate (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.ValidateResponse Validate(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Validate(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest)" />
      <MemberSignature Language="F#" Value="static member Validate : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest -&gt; Microsoft.Azure.Management.WebSites.Models.ValidateResponse" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.Validate (operations, resourceGroupName, validateRequest)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.ValidateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="validateRequest">
            Fordern Sie hinsichtlich der Ressourcen, um zu überprüfen.
            </param>
        <summary>
            Überprüfen Sie, ob eine Ressource erstellt werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüfen Sie, ob eine Ressource erstellt werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt; ValidateAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt; ValidateAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateAsync (operations, resourceGroupName, validateRequest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ValidateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="validateRequest">
            Fordern Sie hinsichtlich der Ressourcen, um zu überprüfen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüfen Sie, ob eine Ressource erstellt werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüfen Sie, ob eine Ressource erstellt werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMove">
      <MemberSignature Language="C#" Value="public static void ValidateMove (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateMove(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMove(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ValidateMove (operations As IWebSiteManagementClient, resourceGroupName As String, moveResourceEnvelope As CsmMoveResourceEnvelope)" />
      <MemberSignature Language="F#" Value="static member ValidateMove : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope -&gt; unit" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMove (operations, resourceGroupName, moveResourceEnvelope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="moveResourceEnvelope">
            Objekt, das Verschieben die Ressource darstellt.
            </param>
        <summary>
            Überprüfen Sie, ob eine Ressource verschoben werden kann.
            </summary>
        <remarks>
            Überprüfen Sie, ob eine Ressource verschoben werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidateMoveAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidateMoveAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMoveAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.ValidateMoveAsync (operations, resourceGroupName, moveResourceEnvelope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;ValidateMoveAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="moveResourceEnvelope">
            Objekt, das Verschieben die Ressource darstellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüfen Sie, ob eine Ressource verschoben werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüfen Sie, ob eine Ressource verschoben werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnet">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails VerifyHostingEnvironmentVnet (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails VerifyHostingEnvironmentVnet(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnet(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.VnetParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VerifyHostingEnvironmentVnet (operations As IWebSiteManagementClient, parameters As VnetParameters) As VnetValidationFailureDetails" />
      <MemberSignature Language="F#" Value="static member VerifyHostingEnvironmentVnet : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.VnetParameters -&gt; Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnet (operations, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            VNET-Informationen
            </param>
        <summary>
            Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt; VerifyHostingEnvironmentVnetAsync (this Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt; VerifyHostingEnvironmentVnetAsync(class Microsoft.Azure.Management.WebSites.IWebSiteManagementClient operations, class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnetAsync(Microsoft.Azure.Management.WebSites.IWebSiteManagementClient,Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyHostingEnvironmentVnetAsync : Microsoft.Azure.Management.WebSites.IWebSiteManagementClient * Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;" Usage="Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions.VerifyHostingEnvironmentVnetAsync (operations, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.WebSites.WebSiteManagementClientExtensions/&lt;VerifyHostingEnvironmentVnetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" RefType="this" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="parameters">
            VNET-Informationen
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>