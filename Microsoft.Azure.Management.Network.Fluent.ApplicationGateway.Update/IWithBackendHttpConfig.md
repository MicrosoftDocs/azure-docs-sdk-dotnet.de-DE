<Type Name="IWithBackendHttpConfig" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfig" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfig" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfig" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfig = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Anwendung Gateway Updates, sodass Back-End-HTTP-Konfigurationen ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.DefineBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineBackendHttpConfiguration (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithBackendHttpConfig.DefineBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein eindeutiger Name für die Back-End-HTTP-Konfiguration.</param>
        <summary>
            Beginn der Definition einer neuen Anwendung Gateway Back-End-HTTP-Konfiguration an das Gateway angefügt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Definition des Back-End-HTTP-Konfiguration.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate UpdateBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate UpdateBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.UpdateBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate" Usage="iWithBackendHttpConfig.UpdateBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackendHttpConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name einer vorhandenen Back-End-HTTP-Konfiguration auf diese Anwendungsgateway.</param>
        <summary>
            Startet das Update einer Back-End-HTTP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithBackendHttpConfig.WithoutBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithBackendHttpConfig.WithoutBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name einer vorhandenen Back-End-HTTP-Konfiguration auf diese Anwendungsgateway.</param>
        <summary>
            Entfernt die angegebene Back-End-HTTP-Konfiguration zwischen diesem Anwendungsgateway an.
            Beachten Sie, dass eine Back-End-HTTP-Konfiguration verwiesen wird, indem Sie andere Einstellungen entfernt das Anwendungsgateway umgebrochen werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>