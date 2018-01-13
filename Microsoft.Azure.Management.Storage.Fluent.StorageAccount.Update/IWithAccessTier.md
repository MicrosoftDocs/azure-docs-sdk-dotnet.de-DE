<Type Name="IWithAccessTier" FullName="Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier">
  <TypeSignature Language="C#" Value="public interface IWithAccessTier" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAccessTier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAccessTier" />
  <TypeSignature Language="F#" Value="type IWithAccessTier = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine BLOB-Speicher-Konto Update Stufe ermöglicht zugriffstarifs angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAccessTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithAccessTier (Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate WithAccessTier(valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IWithAccessTier.WithAccessTier(Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier)" />
      <MemberSignature Language="F#" Value="abstract member WithAccessTier : Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier -&gt; Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate" Usage="iWithAccessTier.WithAccessTier accessTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="accessTier" Type="Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier" />
      </Parameters>
      <Docs>
        <param name="accessTier">Der Wert für den Access-Ebene.</param>
        <summary>
            Gibt die Access-Ebene für die Abrechnung verwendet.
            Zugriffstarifs kann mehr als einmal alle 7 Tage (168 Stunden) geändert werden.
            Zugriffstarifs kann nicht für StandardLRS, StandardGRS, StandardRAGRS oder PremiumLRS Kontotypen festgelegt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Aktualisierung des Speicher-Dienstkontos.</return>
      </Docs>
    </Member>
  </Members>
</Type>