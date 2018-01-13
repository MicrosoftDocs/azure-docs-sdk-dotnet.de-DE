<Type Name="IWithMonitoringConfiguration" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithMonitoringConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMonitoringConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMonitoringConfiguration" />
  <TypeSignature Language="F#" Value="type IWithMonitoringConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Traffic Manager Profil Update ermöglichen die Überwachungskonfiguration Endpunkt angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Verwendung von HTTP-Überwachung für die Endpunkte, die prüft, ob HTTP 200 Antwort aus dem Pfad "/" in regelmäßigen Abständen über Port 80 angeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Traffic Manager-Profil Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpMonitoring (port As Integer, path As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port">Die Überwachung Port.</param>
        <param name="path">Der Überwachungspfad.</param>
        <summary>
            Geben Sie die HTTP-Überwachung für die Endpunkte, die für HTTP 200-Antwort vom angegebenen Pfad in regelmäßigen Abständen überprüft, die mithilfe des angegebenen Ports.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Traffic Manager-Profil Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpsMonitoring" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : unit -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Verwendung von HTTPS-Überwachung für die Endpunkte, die prüft, ob HTTPS 200 Antwort aus dem Pfad "/" in regelmäßigen Abständen über Port 443 angeben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Traffic Manager-Profil Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithHttpsMonitoring">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring (int port, string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate WithHttpsMonitoring(int32 port, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IWithMonitoringConfiguration.WithHttpsMonitoring(System.Int32,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHttpsMonitoring (port As Integer, path As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithHttpsMonitoring : int * string -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate" Usage="iWithMonitoringConfiguration.WithHttpsMonitoring (port, path)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="port">Die Überwachung Port.</param>
        <param name="path">Der Überwachungspfad.</param>
        <summary>
            Geben Sie die HTTPS-Überwachung für die Endpunkte, die HTTPS-200-Antwort vom angegebenen Pfad in regelmäßigen Abständen überprüft, die mithilfe des angegebenen Ports.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Traffic Manager-Profil Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>