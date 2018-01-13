<Type Name="IWithIPConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig">
  <TypeSignature Language="C#" Value="public interface IWithIPConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPConfig" />
  <TypeSignature Language="F#" Value="type IWithIPConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase von einer Anwendung Gateway Update festlegen, dass IP-Konfigurationen ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.DefineDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineDefaultIPConfiguration () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithIPConfig.DefineDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beginn der Definition die Standard-IP-Konfiguration.
            Wenn bereits eine standardmäßige IP-Konfiguration vorhanden ist, wird er dies entspricht dem <code>updateDefaultIPConfiguration()</code>.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die erste Phase eines Updates der IP-Konfiguration.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateDefaultIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateDefaultIPConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateDefaultIPConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateDefaultIPConfiguration () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateDefaultIPConfiguration : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateDefaultIPConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet das Update der Standardkonfiguration von IP-d. h. der einzige vorhanden ist, vorausgesetzt, dass nur eine vorhanden ist, IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die erste Phase eines Updates der IP-Konfiguration.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate UpdateIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.UpdateIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate" Usage="iWithIPConfig.UpdateIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName">Der Name einer vorhandenen IP-Konfiguration.</param>
        <summary>
            Startet das Update einer vorhandenen IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die erste Phase eines Updates der IP-Konfiguration.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration (string ipConfigurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutIPConfiguration(string ipConfigurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithIPConfig.WithoutIPConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPConfiguration (ipConfigurationName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithIPConfig.WithoutIPConfiguration ipConfigurationName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipConfigurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipConfigurationName">Der Name der IP-Konfiguration entfernen.</param>
        <summary>
            Entfernt die angegebene IP-Konfiguration.
            Beachten Sie, dass entfernen eine IP-Konfiguration auf die anderen Einstellungen verweist das Anwendungsgateway unterbrochen werden kann.
            Darüber hinaus muss mindestens eine IP-Konfiguration für das Anwendungsgateway Funktion vorhanden sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>