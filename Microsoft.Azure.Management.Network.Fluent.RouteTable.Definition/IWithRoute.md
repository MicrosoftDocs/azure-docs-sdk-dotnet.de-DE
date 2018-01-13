<Type Name="IWithRoute" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute">
  <TypeSignature Language="C#" Value="public interface IWithRoute" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoute" />
  <TypeSignature Language="F#" Value="type IWithRoute = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Tabellendefinition Route Routen hinzu, sodass.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt; DefineRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.DefineRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRoute (name As String) As IBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;" Usage="iWithRoute.DefineRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Definition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Route.</param>
        <summary>
            Beginn der Definition eine neue Route die Routentabelle hinzu.
            Die Definition muss mit einem Aufruf von Route.DefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute (string destinationAddressPrefix, Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRoute(string destinationAddressPrefix, class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRoute(System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoute (destinationAddressPrefix As String, nextHop As RouteNextHopType) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRoute : string * Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRoute (destinationAddressPrefix, nextHop)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="nextHop" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</param>
        <param name="nextHop">Der Typ des nächsten Hops.</param>
        <summary>
            Erstellt eine Route nicht virtuelle Gerät an.
            Der Name wird automatisch generiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithRouteViaVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance (string destinationAddressPrefix, string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate WithRouteViaVirtualAppliance(string destinationAddressPrefix, string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithRoute.WithRouteViaVirtualAppliance(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRouteViaVirtualAppliance (destinationAddressPrefix As String, ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRouteViaVirtualAppliance : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate" Usage="iWithRoute.WithRouteViaVirtualAppliance (destinationAddressPrefix, ipAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="destinationAddressPrefix">Das Ziel-Adresspräfix, ausgedrückt in der CIDR-Notation für die Route zuweisen.</param>
        <param name="ipAddress">Die IP-Adresse dem virtuellen Gerät aus, um den Datenverkehr über weiterzuleiten.</param>
        <summary>
            Erstellt eine Route über ein virtuelles Gerät.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>