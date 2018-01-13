<Type Name="IWithRoute" FullName="Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute">
  <TypeSignature Language="C#" Value="public interface IWithRoute" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoute" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoute" />
  <TypeSignature Language="F#" Value="type IWithRoute = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Tabellendefinition Route zum Hinzufügen, sodass entfernen oder Ändern von Routen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt; DefineRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt; DefineRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.DefineRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRoute (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;" Usage="iWithRoute.DefineRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Route.</param>
        <summary>
            Beginn der Definition eine neue Route die Routentabelle hinzu.
            Die Definition muss mit einem Aufruf von Route.UpdateDefinitionStages.WithAttach.attach() abgeschlossen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate UpdateRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate UpdateRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.UpdateRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRoute (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate" Usage="iWithRoute.UpdateRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eine vorhandene Route.</param>
        <summary>
            Startet das Update für eine vorhandene Route für die Routentabelle.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithoutRoute (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithoutRoute(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithoutRoute(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRoute (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRoute : string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithoutRoute name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der eine vorhandene Route für die Routentabelle.</param>
        <summary>
            Entfernt die angegebene Route aus der Routentabelle an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRoute (string destinationAddressPrefix, Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRoute(string destinationAddressPrefix, class Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType nextHop) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithRoute(System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoute (destinationAddressPrefix As String, nextHop As RouteNextHopType) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRoute : string * Microsoft.Azure.Management.Network.Fluent.Models.RouteNextHopType -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithRoute (destinationAddressPrefix, nextHop)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
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
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithRouteViaVirtualAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRouteViaVirtualAppliance (string destinationAddressPrefix, string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate WithRouteViaVirtualAppliance(string destinationAddressPrefix, string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IWithRoute.WithRouteViaVirtualAppliance(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRouteViaVirtualAppliance (destinationAddressPrefix As String, ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRouteViaVirtualAppliance : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate" Usage="iWithRoute.WithRouteViaVirtualAppliance (destinationAddressPrefix, ipAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.RouteTable.Update.IUpdate</ReturnType>
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
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>