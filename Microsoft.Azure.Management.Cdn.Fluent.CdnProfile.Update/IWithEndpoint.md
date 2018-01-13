<Type Name="IWithEndpoint" FullName="Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint">
  <TypeSignature Language="C#" Value="public interface IWithEndpoint : Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpoint implements class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpoint&#xA;Implements IBeta, IWithEndpointBeta" />
  <TypeSignature Language="F#" Value="type IWithEndpoint = interface&#xA;    interface IWithEndpointBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpointBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Stufe der Aktualisierung eines CDN-Profils, das die Endpunkte für das Profil ändern können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.DefineNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewEndpoint (name As String) As IStandardEndpoint(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineNewEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.StandardEndpoint.IStandardEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name für den Endpunkt.</param>
        <summary>
            Startet die Definition eines neuen Endpunkts an das CDN-Profil angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Endpunktdefinition einer.</return>
      </Docs>
    </Member>
    <Member MemberName="DefineNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewPremiumEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt; DefineNewPremiumEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.DefineNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewPremiumEndpoint (name As String) As IPremiumEndpoint(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;" Usage="iWithEndpoint.DefineNewPremiumEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateDefinition.Blank.PremiumEndpoint.IPremiumEndpoint&lt;Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein Name für den neuen Endpunkt.</param>
        <summary>
            Startet die Definition eines neuen Endpunkts dieses Premium Verizon CDN-Profil zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Endpunktdefinition einer.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint UpdateEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint UpdateEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.UpdateEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateEndpoint (name As String) As IUpdateStandardEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdateEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint" Usage="iWithEndpoint.UpdateEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdateStandardEndpoint.IUpdateStandardEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name eines vorhandenen Endpunkts.</param>
        <summary>
            Startet die Beschreibung eines Updates einen vorhandenen Endpunkt im aktuellen Profil.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Aktualisierung des Endpunkts.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint UpdatePremiumEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint UpdatePremiumEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.UpdatePremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePremiumEndpoint (name As String) As IUpdatePremiumEndpoint" />
      <MemberSignature Language="F#" Value="abstract member UpdatePremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint" Usage="iWithEndpoint.UpdatePremiumEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnEndpoint.UpdatePremiumEndpoint.IUpdatePremiumEndpoint</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Endpunkts.</param>
        <summary>
            Startet die Beschreibung eines Updates einen vorhandenen Endpunkt im aktuellen Verizon Premium-Profil an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Aktualisierung des Endpunkts.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithNewEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewEndpoint (endpointOriginHostname As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithNewEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname">ein Endpunkt Hostname des Ursprungs.</param>
        <summary>
            Fügt einen neuen Endpunkt hinzu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPremiumEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewPremiumEndpoint (string endpointOriginHostname);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithNewPremiumEndpoint(string endpointOriginHostname) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithNewPremiumEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPremiumEndpoint (endpointOriginHostname As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewPremiumEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithNewPremiumEndpoint endpointOriginHostname" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endpointOriginHostname" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endpointOriginHostname">der Hostname des Ursprungs Endpunkt.</param>
        <summary>
            Aktuelle Premium Verizon CDN-Profil hinzugefügt neuen Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutEndpoint">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithoutEndpoint (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate WithoutEndpoint(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IWithEndpoint.WithoutEndpoint(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutEndpoint (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutEndpoint : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate" Usage="iWithEndpoint.WithoutEndpoint name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CdnProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name eines vorhandenen Endpunkts.</param>
        <summary>
            Entfernt einen Endpunkt aus dem Profil.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des CDN-Profil-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>