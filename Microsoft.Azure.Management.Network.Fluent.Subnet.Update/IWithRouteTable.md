<Type Name="IWithRouteTable" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable">
  <TypeSignature Language="C#" Value="public interface IWithRouteTable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRouteTable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRouteTable" />
  <TypeSignature Language="F#" Value="type IWithRouteTable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Subnetzes aktualisieren zulassen, geben Sie eine Routingtabelle mit dem Subnetz zuordnen, oder entfernen eine vorhandene Zuordnung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(class Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(Microsoft.Azure.Management.Network.Fluent.IRouteTable)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (routeTable As IRouteTable) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : Microsoft.Azure.Management.Network.Fluent.IRouteTable -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable routeTable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTable" />
      </Parameters>
      <Docs>
        <param name="routeTable">Eine vorhandene Routentabelle zugeordnet.</param>
        <summary>
            Gibt eine vorhandene Routentabelle mit dem Subnetz zuordnen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithExistingRouteTable(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithExistingRouteTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (resourceId As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithExistingRouteTable resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId">Die Ressourcen-ID einer vorhandenen Tabelle für die Route.</param>
        <summary>
            Gibt eine vorhandene Routentabelle mit dem Subnetz zuordnen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate WithoutRouteTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IWithRouteTable.WithoutRouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRouteTable () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRouteTable : unit -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate" Usage="iWithRouteTable.WithoutRouteTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Entfernt die Zuordnung zu einer Routentabelle an, sofern vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>