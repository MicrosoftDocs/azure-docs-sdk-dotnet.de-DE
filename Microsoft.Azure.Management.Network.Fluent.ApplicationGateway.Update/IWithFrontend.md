<Type Name="IWithFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend">
  <TypeSignature Language="C#" Value="public interface IWithFrontend" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend" />
  <TypeSignature Language="F#" Value="type IWithFrontend = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines um Front-End-IP-Konfigurationen zu ändern, sodass Anwendung Gateway-Updates.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefinePrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePrivateFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die Definition der standardmäßige private Front-End-IP-Konfiguration, erstellen einen, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Front-End-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="DefinePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefinePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.DefinePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePublicFrontend () As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithFrontend.DefinePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die Definition der standardmäßige öffentliche Front-End-IP-Konfiguration, erstellen einen, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Front-End-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdateFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdateFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdateFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName">Der Name einer vorhandenen Front-End-IP-Konfiguration.</param>
        <summary>
            Startet das Update einer vorhandenen Front-End-IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase der Aktualisierung der Front-End-IP-Konfiguration.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate UpdatePublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.UpdatePublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate" Usage="iWithFrontend.UpdatePublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayFrontend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beginnt die Aktualisierung der öffentliche Front-End-IP-Konfiguration an, falls vorhanden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase eines Front-End-Update oder Null, wenn keine öffentliche Front-End-vorhanden ist.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend (string frontendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutFrontend(string frontendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutFrontend(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFrontend (frontendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFrontend : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutFrontend frontendName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frontendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="frontendName">Der Name der Front-End-IP-Konfiguration entfernen.</param>
        <summary>
            Entfernt die angegebene Front-End-IP-Konfiguration.
            Beachten Sie, dass ein Front-End-verwiesen wird, indem Sie andere Einstellungen entfernen das Anwendungsgateway umgebrochen werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrivateFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass das Anwendungsgateway sollte nicht privat sein, d. h. seine Endponts sollte nicht intern von innerhalb des virtuellen Netzwerks zugänglich.
            Beachten Sie, wenn alle anderen Einstellungen verweisen auf das private Front-End vorhanden sind, entfernen sie das Anwendungsgateway unterbrechen kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithFrontend.WithoutPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPublicFrontend () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithFrontend.WithoutPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass das Anwendungsgateway Internetzugriff nicht sein sollte.
            Beachten Sie, wenn alle anderen Einstellungen verweisen auf das öffentliche Front-End vorhanden sind, entfernen sie das Anwendungsgateway unterbrechen kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>