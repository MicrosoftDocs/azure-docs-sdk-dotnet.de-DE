<Type Name="IWithIdleTimout" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimout" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimout" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimout" />
  <TypeSignature Language="F#" Value="type IWithIdleTimout = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine öffentliche IP-Adresse aktualisieren, sodass das Leerlauftimeout geändert werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIdleTimout.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIdleTimout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes">Die Länge der Zeit in Minuten.</param>
        <summary>
            Gibt den Timeoutwert (in Minuten) für eine Verbindung im Leerlauf an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Ressource-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>